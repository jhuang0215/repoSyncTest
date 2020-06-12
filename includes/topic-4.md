Topic 4500 Runtime extension is not available: include

# Runtime extension is not available: include (500) #

The requested URL /content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4.html resulted in an error in /apps/core/wcm/components/page/v2/page/page.html.

### Exception: ###

``````````
org.apache.sling.scripting.sightly.SightlyException: Runtime extension is not available: include
	at org.apache.sling.scripting.sightly.impl.engine.runtime.RenderContextImpl.call(RenderContextImpl.java:75)
	at org.apache.sling.scripting.sightly.apps.core.wcm.components.page.v2.page.headlibs_html$1.render(headlibs_html.java:102)
	at org.apache.sling.scripting.sightly.render.RenderUnit.render(RenderUnit.java:50)
	at org.apache.sling.scripting.sightly.render.RenderUnit.callUnit(RenderUnit.java:87)
	at org.apache.sling.scripting.sightly.apps.core.wcm.components.page.v2.page.head_html$1.render(head_html.java:195)
	at org.apache.sling.scripting.sightly.render.RenderUnit.render(RenderUnit.java:50)
	at org.apache.sling.scripting.sightly.render.RenderUnit.callUnit(RenderUnit.java:87)
	at org.apache.sling.scripting.sightly.apps.core.wcm.components.page.v2.page.page_html.render(page_html.java:76)
	at org.apache.sling.scripting.sightly.render.RenderUnit.render(RenderUnit.java:50)
	at org.apache.sling.scripting.sightly.impl.engine.SightlyCompiledScript.eval(SightlyCompiledScript.java:60)
	at org.apache.sling.scripting.core.impl.DefaultSlingScript.call(DefaultSlingScript.java:386)
	at org.apache.sling.scripting.core.impl.DefaultSlingScript.eval(DefaultSlingScript.java:184)
	at org.apache.sling.scripting.core.impl.DefaultSlingScript.service(DefaultSlingScript.java:491)
	at org.apache.sling.engine.impl.request.RequestData.service(RequestData.java:552)
	at org.apache.sling.engine.impl.filter.SlingComponentFilterChain.render(SlingComponentFilterChain.java:44)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:82)
	at com.day.cq.wcm.core.impl.WCMDeveloperModeFilter.doFilter(WCMDeveloperModeFilter.java:119)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.WCMDebugFilter.doFilterWithErrorHandling(WCMDebugFilter.java:192)
	at com.day.cq.wcm.core.impl.WCMDebugFilter.doFilter(WCMDebugFilter.java:159)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.dynamicinclude.IncludeTagFilter.doFilter(IncludeTagFilter.java:71)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.WCMComponentFilter.doFilter(WCMComponentFilter.java:278)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.page.PageLockFilter.doFilter(PageLockFilter.java:91)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.personalization.impl.TargetComponentFilter.doFilter(TargetComponentFilter.java:94)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.csrf.impl.CSRFFilter.doFilter(CSRFFilter.java:217)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.SlingRequestProcessorImpl.processComponent(SlingRequestProcessorImpl.java:282)
	at org.apache.sling.engine.impl.SlingRequestProcessorImpl.dispatchRequest(SlingRequestProcessorImpl.java:322)
	at org.apache.sling.engine.impl.request.SlingRequestDispatcher.dispatch(SlingRequestDispatcher.java:211)
	at org.apache.sling.engine.impl.request.SlingRequestDispatcher.include(SlingRequestDispatcher.java:104)
	at com.day.cq.wcm.core.impl.WCMComponentFilter$ForwardRequestDispatcher.include(WCMComponentFilter.java:516)
	at org.apache.jsp.libs.cq.Page.Page_jsp._jspService(Page_jsp.java:117)
	at org.apache.sling.scripting.jsp.jasper.runtime.HttpJspBase.service(HttpJspBase.java:70)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:725)
	at org.apache.sling.scripting.jsp.jasper.servlet.JspServletWrapper.service(JspServletWrapper.java:502)
	at org.apache.sling.scripting.jsp.jasper.servlet.JspServletWrapper.service(JspServletWrapper.java:449)
	at org.apache.sling.scripting.jsp.JspScriptEngineFactory.callJsp(JspScriptEngineFactory.java:342)
	at org.apache.sling.scripting.jsp.JspScriptEngineFactory.access$100(JspScriptEngineFactory.java:97)
	at org.apache.sling.scripting.jsp.JspScriptEngineFactory$JspScriptEngine.eval(JspScriptEngineFactory.java:603)
	at org.apache.sling.scripting.core.impl.DefaultSlingScript.call(DefaultSlingScript.java:388)
	at org.apache.sling.scripting.core.impl.DefaultSlingScript.eval(DefaultSlingScript.java:184)
	at org.apache.sling.scripting.core.impl.DefaultSlingScript.service(DefaultSlingScript.java:491)
	at org.apache.sling.engine.impl.request.RequestData.service(RequestData.java:552)
	at org.apache.sling.engine.impl.filter.SlingComponentFilterChain.render(SlingComponentFilterChain.java:44)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:82)
	at com.day.cq.wcm.core.impl.WCMDebugFilter.doFilter(WCMDebugFilter.java:156)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.WCMComponentFilter.filterRootInclude(WCMComponentFilter.java:375)
	at com.day.cq.wcm.core.impl.WCMComponentFilter.doFilter(WCMComponentFilter.java:190)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.page.PageLockFilter.doFilter(PageLockFilter.java:91)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.personalization.impl.TargetComponentFilter.doFilter(TargetComponentFilter.java:94)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.SlingRequestProcessorImpl.processComponent(SlingRequestProcessorImpl.java:282)
	at org.apache.sling.engine.impl.filter.RequestSlingFilterChain.render(RequestSlingFilterChain.java:49)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:82)
	at org.apache.sling.dynamicinclude.SyntheticResourceFilter.doFilter(SyntheticResourceFilter.java:66)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:78)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:78)
	at com.day.cq.wcm.core.impl.warp.TimeWarpFilter.doFilter(TimeWarpFilter.java:109)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.cq.social.ugcbase.security.impl.SaferSlingPostServlet.doFilter(SaferSlingPostServlet.java:114)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:78)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:78)
	at com.day.cq.dam.core.impl.servlet.ActivityRecordHandler.doFilter(ActivityRecordHandler.java:141)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.dam.core.impl.assetlinkshare.AdhocAssetShareAuthHandler.doFilter(AdhocAssetShareAuthHandler.java:437)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.rest.impl.servlet.ApiResourceFilter.doFilter(ApiResourceFilter.java:70)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.requests.logging.impl.RequestLoggerImpl.doFilter(RequestLoggerImpl.java:134)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.rest.assets.impl.AssetContentDispositionFilter.doFilter(AssetContentDispositionFilter.java:96)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.AuthoringUIModeServiceImpl.doFilter(AuthoringUIModeServiceImpl.java:297)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.mobile.core.impl.redirect.RedirectFilter.doFilter(RedirectFilter.java:248)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.dynamicinclude.CacheControlFilter.doFilter(CacheControlFilter.java:67)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.debug.RequestProgressTrackerLogFilter.doFilter(RequestProgressTrackerLogFilter.java:107)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.cq.social.commons.cors.CORSAuthenticationFilter.doFilter(CORSAuthenticationFilter.java:91)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.foundation.forms.FormsHandlingServletHelper.handleFilter(FormsHandlingServletHelper.java:226)
	at com.day.cq.wcm.foundation.forms.impl.FormsHandlingServlet.doFilter(FormsHandlingServlet.java:138)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.optout.impl.OptOutFilter.doFilter(OptOutFilter.java:76)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.foundation.forms.FormsHandlingServletHelper.handleFilter(FormsHandlingServletHelper.java:226)
	at com.adobe.cq.wcm.core.components.internal.servlets.CoreFormHandlingServlet.doFilter(CoreFormHandlingServlet.java:126)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.foundation.forms.FormsHandlingServletHelper.handleFilter(FormsHandlingServletHelper.java:226)
	at com.adobe.cq.wcm.core.components.internal.servlets.CoreFormHandlingServlet.doFilter(CoreFormHandlingServlet.java:126)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.day.cq.wcm.core.impl.WCMRequestFilter.doFilter(WCMRequestFilter.java:90)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.cq.history.impl.HistoryRequestFilter.doFilter(HistoryRequestFilter.java:122)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.cq.mcm.campaign.servlets.CampaignCopyTracker.doFilter(CampaignCopyTracker.java:100)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.rewriter.impl.RewriterFilter.doFilter(RewriterFilter.java:87)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.httpcache.impl.InnerCacheFilter.doFilter(InnerCacheFilter.java:81)
	at com.adobe.granite.httpcache.impl.InnerCacheFilter.doFilter(InnerCacheFilter.java:60)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.i18n.impl.I18NFilter.doFilter(I18NFilter.java:131)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at com.adobe.granite.csrf.impl.CSRFFilter.doFilter(CSRFFilter.java:217)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.security.impl.ContentDispositionFilter.doFilter(ContentDispositionFilter.java:152)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:78)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:78)
	at com.adobe.granite.resourceresolverhelper.impl.ResourceResolverHelperImpl.doFilter(ResourceResolverHelperImpl.java:83)
	at org.apache.sling.engine.impl.filter.AbstractSlingFilterChain.doFilter(AbstractSlingFilterChain.java:72)
	at org.apache.sling.engine.impl.SlingRequestProcessorImpl.doProcessRequest(SlingRequestProcessorImpl.java:151)
	at org.apache.sling.engine.impl.SlingRequestProcessorImpl.processRequest(SlingRequestProcessorImpl.java:247)
	at com.microsoft.learning.core.sync.crx.model.CrxPage.getHtml(CrxPage.java:46)
	at com.microsoft.learning.core.sync.crx.model.CrxPage.getDoc(CrxPage.java:57)
	at com.microsoft.learning.core.export.links.TopicPageToMarkdownLink.sync(TopicPageToMarkdownLink.java:33)
	at com.microsoft.learning.core.sync.repos.ModelNodeLink.syncPass(ModelNodeLink.java:86)
	at com.microsoft.learning.core.export.ExportProcessor.run(ExportProcessor.java:304)
	at com.microsoft.learning.core.services.impl.GitHubExportServiceImpl.export(GitHubExportServiceImpl.java:61)
	at com.microsoft.learning.core.workflows.GitHubExportProcess.execute(GitHubExportProcess.java:28)
	at com.adobe.granite.workflow.core.job.HandlerBase.executeProcess(HandlerBase.java:195)
	at com.adobe.granite.workflow.core.job.JobHandler.process(JobHandler.java:260)
	at org.apache.sling.event.impl.jobs.JobConsumerManager$JobConsumerWrapper.process(JobConsumerManager.java:502)
	at org.apache.sling.event.impl.jobs.queues.JobQueueImpl.startJob(JobQueueImpl.java:293)
	at org.apache.sling.event.impl.jobs.queues.JobQueueImpl.access$100(JobQueueImpl.java:60)
	at org.apache.sling.event.impl.jobs.queues.JobQueueImpl$1.run(JobQueueImpl.java:229)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
	at java.base/java.lang.Thread.run(Thread.java:834)
``````````

### Request Progress: ###

``````````
0 TIMER_START{Request Processing}
    268 COMMENT timer_end format is {<elapsed microseconds>,<timer name>} <optional message>
    544 LOG Method=GET, PathInfo=null
    636 TIMER_START{ResourceResolution}
  17779 TIMER_END{16864,ResourceResolution} URI=/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4.html resolves to Resource=JcrNodeResource, type=cq:Page, superType=null, path=/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4
  18139 LOG Resource Path Info: SlingRequestPathInfo: path='/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4', selectorString='null', extension='html', suffix='null'
  18146 TIMER_START{ServletResolution}
  18278 TIMER_START{resolveServlet(/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4)}
 322357 TIMER_END{303998,resolveServlet(/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4)} Using servlet /libs/cq/Page/Page.jsp
 322736 TIMER_END{304509,ServletResolution} URI=/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4.html handled by Servlet=/libs/cq/Page/Page.jsp
 322848 LOG Applying Requestfilters
 323119 LOG Calling filter: com.adobe.granite.resourceresolverhelper.impl.ResourceResolverHelperImpl
 323608 LOG Calling filter: org.apache.sling.security.impl.ContentDispositionFilter
 323860 LOG Calling filter: com.adobe.granite.csrf.impl.CSRFFilter
 324105 LOG Calling filter: org.apache.sling.i18n.impl.I18NFilter
 324368 LOG Calling filter: com.adobe.granite.httpcache.impl.InnerCacheFilter
 324694 LOG Calling filter: org.apache.sling.rewriter.impl.RewriterFilter
 324948 LOG Calling filter: com.adobe.cq.mcm.campaign.servlets.CampaignCopyTracker
 325368 LOG Calling filter: com.adobe.cq.history.impl.HistoryRequestFilter
 343844 LOG Calling filter: com.day.cq.wcm.core.impl.WCMRequestFilter
 344114 LOG Calling filter: com.adobe.cq.wcm.core.components.internal.servlets.CoreFormHandlingServlet
 344364 LOG Calling filter: com.adobe.cq.wcm.core.components.internal.servlets.CoreFormHandlingServlet
 344609 LOG Calling filter: com.adobe.granite.optout.impl.OptOutFilter
 344874 LOG Calling filter: com.day.cq.wcm.foundation.forms.impl.FormsHandlingServlet
 345118 LOG Calling filter: com.adobe.cq.social.commons.cors.CORSAuthenticationFilter
 345355 LOG Calling filter: org.apache.sling.engine.impl.debug.RequestProgressTrackerLogFilter
 345585 LOG Calling filter: org.apache.sling.dynamicinclude.CacheControlFilter
 345831 LOG Calling filter: com.day.cq.wcm.mobile.core.impl.redirect.RedirectFilter
 346069 LOG Calling filter: com.day.cq.wcm.core.impl.AuthoringUIModeServiceImpl
 346926 LOG Calling filter: com.adobe.granite.rest.assets.impl.AssetContentDispositionFilter
 347108 LOG Calling filter: com.adobe.granite.requests.logging.impl.RequestLoggerImpl
 348893 LOG Calling filter: com.adobe.granite.rest.impl.servlet.ApiResourceFilter
 364361 LOG Calling filter: com.day.cq.dam.core.impl.assetlinkshare.AdhocAssetShareAuthHandler
 364518 LOG Calling filter: com.day.cq.dam.core.impl.servlet.ActivityRecordHandler
 365311 LOG Calling filter: com.adobe.cq.social.ugcbase.security.impl.SaferSlingPostServlet
 365571 LOG Calling filter: com.day.cq.wcm.core.impl.warp.TimeWarpFilter
 366566 LOG Calling filter: org.apache.sling.dynamicinclude.SyntheticResourceFilter
 366727 LOG Applying Componentfilters
 366971 LOG Calling filter: com.day.cq.personalization.impl.TargetComponentFilter
 367227 LOG Calling filter: com.day.cq.wcm.core.impl.page.PageLockFilter
 367499 LOG Calling filter: com.day.cq.wcm.core.impl.WCMComponentFilter
 375650 LOG Calling filter: com.day.cq.wcm.core.impl.WCMDebugFilter
 375871 TIMER_START{/libs/cq/Page/Page.jsp#0}
 559795 LOG Including resource JcrNodeResource, type=microsoft-learning/components/structure/topic-page, superType=null, path=/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4/jcr:content (SlingRequestPathInfo: path='/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4/jcr:content', selectorString='null', extension='html', suffix='null')
 559931 TIMER_START{resolveServlet(/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4/jcr:content)}
1023699 TIMER_END{463690,resolveServlet(/content/microsoft-learning/ilt-course/section-1/lesson-1/topic-4/jcr:content)} Using servlet /apps/core/wcm/components/page/v2/page/page.html
1023825 LOG Applying Includefilters
1024084 LOG Calling filter: com.adobe.granite.csrf.impl.CSRFFilter
1025332 LOG Calling filter: com.day.cq.personalization.impl.TargetComponentFilter
1025509 LOG Calling filter: com.day.cq.wcm.core.impl.page.PageLockFilter
1025681 LOG Calling filter: com.day.cq.wcm.core.impl.WCMComponentFilter
1027711 LOG Calling filter: org.apache.sling.dynamicinclude.IncludeTagFilter
1028013 LOG Calling filter: com.day.cq.wcm.core.impl.WCMDebugFilter
1028356 LOG Calling filter: com.day.cq.wcm.core.impl.WCMDeveloperModeFilter
1028528 TIMER_START{/apps/core/wcm/components/page/v2/page/page.html#1}
1227659 LOG Found processor for post processing ProcessorConfiguration: {contentTypes=[text/html], order=1, active=true, valid=true, processErrorResponse=true, pipeline=(generator=Config(type=htmlparser, config=JcrPropertyMap [node=Node[NodeDelegate{tree=/apps/noa/config/rewriter/versioned-clientlibs/generator-htmlparser: { jcr:primaryType = nt:unstructured, includeTags = [A, /A, IMG, AREA, FORM, BASE, LINK, SCRIPT, BODY, /BODY]}}], values={jcr:primaryType=nt:unstructured, includeTags=[Ljava.lang.String;@40397e6b}]), transformers=(Config(type=linkchecker, config={}), Config(type=versioned-clientlibs, config={}), Config(type=gamelinkrewriter, config={}), serializer=Config(type=htmlwriter, config={}))}
18265334 LOG SCRIPT ERROR: Runtime extension is not available: include
18265673 TIMER_END{17237075,/apps/core/wcm/components/page/v2/page/page.html#1}
18268151 LOG Filter timing: filter=com.day.cq.wcm.core.impl.WCMDeveloperModeFilter, inner=17,237, total=17,238, outer=1
18268634 LOG Filter timing: filter=com.day.cq.wcm.core.impl.WCMDebugFilter, inner=17,238, total=17,238, outer=0
18269132 LOG Filter timing: filter=org.apache.sling.dynamicinclude.IncludeTagFilter, inner=17,238, total=17,239, outer=1
18269732 LOG Filter timing: filter=com.day.cq.wcm.core.impl.WCMComponentFilter, inner=17,239, total=17,240, outer=1
18270267 LOG Filter timing: filter=com.day.cq.wcm.core.impl.page.PageLockFilter, inner=17,240, total=17,241, outer=1
18270815 LOG Filter timing: filter=com.day.cq.personalization.impl.TargetComponentFilter, inner=17,241, total=17,242, outer=1
18273751 LOG SCRIPT ERROR: 
18273862 TIMER_END{17897953,/libs/cq/Page/Page.jsp#0}
18274941 LOG Filter timing: filter=com.day.cq.wcm.core.impl.WCMDebugFilter, inner=17,897, total=17,898, outer=1
18275649 LOG Filter timing: filter=com.day.cq.wcm.core.impl.WCMComponentFilter, inner=17,898, total=17,907, outer=9
18276124 LOG Filter timing: filter=com.day.cq.wcm.core.impl.page.PageLockFilter, inner=17,907, total=17,907, outer=0
18279577 LOG Filter timing: filter=org.apache.sling.dynamicinclude.SyntheticResourceFilter, inner=17,909, total=17,910, outer=1
18280051 LOG Filter timing: filter=com.adobe.cq.dtm.reactor.impl.servlets.ClientLibraryFilter, inner=17,910, total=17,910, outer=0
18280625 LOG Filter timing: filter=com.adobe.cq.dam.webdav.impl.io.DamWebdavRequestFilter, inner=17,910, total=17,910, outer=0
18281109 LOG Filter timing: filter=com.day.cq.wcm.core.impl.warp.TimeWarpFilter, inner=17,910, total=17,911, outer=1
18281578 LOG Filter timing: filter=com.adobe.cq.social.ugcbase.security.impl.SaferSlingPostServlet, inner=17,911, total=17,911, outer=0
18282101 LOG Filter timing: filter=com.adobe.cq.dtm.impl.servlets.DTMLibraryCompatibilityFilter, inner=17,911, total=17,911, outer=0
18282705 LOG Filter timing: filter=com.day.cq.dam.core.impl.servlet.DamContentDispositionFilter, inner=17,911, total=17,911, outer=0
18283215 LOG Filter timing: filter=com.day.cq.dam.core.impl.servlet.ActivityRecordHandler, inner=17,911, total=17,912, outer=1
18283778 LOG Filter timing: filter=com.day.cq.dam.core.impl.assetlinkshare.AdhocAssetShareAuthHandler, inner=17,912, total=17,912, outer=0
18284332 LOG Filter timing: filter=com.adobe.granite.rest.impl.servlet.ApiResourceFilter, inner=17,912, total=17,929, outer=17
18284854 LOG Filter timing: filter=com.adobe.granite.requests.logging.impl.RequestLoggerImpl, inner=17,929, total=17,931, outer=2
18285389 LOG Filter timing: filter=com.adobe.granite.rest.assets.impl.AssetContentDispositionFilter, inner=17,931, total=17,932, outer=1
18286076 LOG Filter timing: filter=com.day.cq.wcm.core.impl.AuthoringUIModeServiceImpl, inner=17,932, total=17,932, outer=0
18286592 LOG Filter timing: filter=com.day.cq.wcm.mobile.core.impl.redirect.RedirectFilter, inner=17,932, total=17,932, outer=0
18287075 LOG Filter timing: filter=org.apache.sling.dynamicinclude.CacheControlFilter, inner=17,932, total=17,933, outer=1
18287544 LOG Filter timing: filter=org.apache.sling.engine.impl.debug.RequestProgressTrackerLogFilter, inner=17,933, total=17,933, outer=0
18288048 LOG Filter timing: filter=com.adobe.cq.social.commons.cors.CORSAuthenticationFilter, inner=17,933, total=17,933, outer=0
18288548 LOG Filter timing: filter=com.day.cq.wcm.foundation.forms.impl.FormsHandlingServlet, inner=17,933, total=17,933, outer=0
18289046 LOG Filter timing: filter=com.adobe.granite.optout.impl.OptOutFilter, inner=17,933, total=17,934, outer=1
18289524 LOG Filter timing: filter=com.adobe.cq.wcm.core.components.internal.servlets.CoreFormHandlingServlet, inner=17,934, total=17,934, outer=0
18289989 LOG Filter timing: filter=com.adobe.cq.wcm.core.components.internal.servlets.CoreFormHandlingServlet, inner=17,934, total=17,934, outer=0
18290456 LOG Filter timing: filter=com.day.cq.wcm.core.impl.WCMRequestFilter, inner=17,934, total=17,934, outer=0
18290929 LOG Filter timing: filter=com.adobe.cq.history.impl.HistoryRequestFilter, inner=17,934, total=17,953, outer=19
18291400 LOG Filter timing: filter=com.adobe.cq.mcm.campaign.servlets.CampaignCopyTracker, inner=17,953, total=17,953, outer=0
18291902 LOG Filter timing: filter=org.apache.sling.rewriter.impl.RewriterFilter, inner=17,953, total=17,953, outer=0
18292737 LOG Filter timing: filter=com.adobe.granite.httpcache.impl.InnerCacheFilter, inner=17,953, total=17,954, outer=1
18293259 LOG Filter timing: filter=org.apache.sling.i18n.impl.I18NFilter, inner=17,954, total=17,955, outer=1
18293801 LOG Filter timing: filter=com.adobe.granite.csrf.impl.CSRFFilter, inner=17,955, total=17,955, outer=0
18294306 LOG Filter timing: filter=org.apache.sling.security.impl.ContentDispositionFilter, inner=17,955, total=17,956, outer=1
18294924 LOG Filter timing: filter=com.nintendo.noa.core.filters.impl.RedirectFilter, inner=17,956, total=17,956, outer=0
18295400 LOG Filter timing: filter=org.apache.sling.distribution.servlet.DistributionAgentCreationFilter, inner=17,956, total=17,956, outer=0
18338078 LOG Applying Error filters
18338286 LOG Calling filter: org.apache.sling.i18n.impl.I18NFilter
18338455 LOG Calling filter: org.apache.sling.rewriter.impl.RewriterFilter
18338566 TIMER_START{handleError:throwable=org.apache.sling.scripting.sightly.SightlyException}
18757550 TIMER_END{418930,handleError:throwable=org.apache.sling.scripting.sightly.SightlyException} Using handler org.apache.sling.servlets.resolver.internal.defaults.DefaultErrorHandlerServlet
18814102 LOG Found processor for post processing ProcessorConfiguration: {contentTypes=[text/html], order=1, active=true, valid=true, processErrorResponse=true, pipeline=(generator=Config(type=htmlparser, config=JcrPropertyMap [node=Node[NodeDelegate{tree=/apps/noa/config/rewriter/versioned-clientlibs/generator-htmlparser: { jcr:primaryType = nt:unstructured, includeTags = [A, /A, IMG, AREA, FORM, BASE, LINK, SCRIPT, BODY, /BODY]}}], values={jcr:primaryType=nt:unstructured, includeTags=[Ljava.lang.String;@40397e6b}]), transformers=(Config(type=linkchecker, config={}), Config(type=versioned-clientlibs, config={}), Config(type=gamelinkrewriter, config={}), serializer=Config(type=htmlwriter, config={}))}
19639903 TIMER_END{19639850,Request Processing} Dumping SlingRequestProgressTracker Entries
``````````

--------------------

ApacheSling/2.6 (jetty/9.4.15.v20190215, Java HotSpot(TM) 64-Bit Server VM 11.0.3, Mac OS X 10.14.5 x86\_64)