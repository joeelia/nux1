<template>

  <main>
  	<div class="container-fluid p-0">
            <div class="main-slider-area">
            <div style="position: fixed; top: 0; width: 100%; height: 100%; z-index: -1;">
            	<video  width="100%" height="100%" autoplay loop muted playsinline>  
            		<source src="../assets/images/main-bg.mp4" type="video/mp4" alt="video"> 
            	</video>
            </div>
                <div class="slider-text-area">
                    <h1 class="slider-heading">
                        <span scale="h3" class="smaller-heding">Joe Elia, <small>Full-stack</small>  Developer</span>
                        can help you with
                    </h1>
                    <div class="text-box">
                        <div class="text-box-header"><span class="green-dot"></span></div>
                        <div class="text-box-body">
                            <div class="text-js headline">
                                <vue-typer :text='["Building An MVP","Analytics","JavaScript","WordPress","Laravel"]' :shuffle='true'></vue-typer>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="buttons-area">
                    <a href="#" class="btn btn-slider-dark">Get Free Account</a>
                    <a href="#" class="btn btn-slider-wht">Read the docs</a>
                </div>
            </div>
        </div>
    <section class="channels-section">
            <div class="container-fluid">
                <div class="channels-section-inner">
                    <div class="row">
                        <div class="col-md-4">
                            <a href="#" class="channels-logo"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1170.84 200"><title>channels_full-logo</title><g fill="white"><path d="M326.39,37.64c25.37,0,45.08,17.48,47.82,42.85L349.36,84.6c-2.58-15.25-10.8-23.82-23-23.82-17.32,0-27.6,14.74-27.6,39.42s10.28,39.42,27.6,39.42c12.85,0,21.08-9.08,23.31-25.71l24.85,4.29c-3.08,26.91-21.94,44.56-48.16,44.56-32.06,0-53-24.68-53-62.56S294.33,37.64,326.39,37.64Z"></path><path d="M397.17,40.21h25.37v47h38.91v-47h25.37v120H461.45V110.31H422.54v49.88H397.17Z"></path><path d="M583.14,141.51H537.2l-6.34,18.68h-25.2l42.85-120h23.31l42.86,120h-25.2Zm-7.72-22.28L560.34,75H560l-15.08,44.23Z"></path><path d="M633.35,40.21h26L700,116.48h.34V40.21h25.37v120H699.68L659.06,83.91h-.34v76.28H633.35Z"></path><path d="M757.09,40.21h26.06l40.62,76.27h.34V40.21h25.37v120H823.43L782.81,83.91h-.35v76.28H757.09Z"></path><path d="M880.84,40.21h77.3V63.52H906.21V87.86h47.3v22.28h-47.3v26.74h52.1v23.31H880.84Z"></path><path d="M984.7,40.21h25.37v96.67h50.74v23.31H984.7Z"></path><path d="M1100.74,115.28C1104,133.11,1111,140,1127,140c11.83,0,18.51-4.29,18.51-11.83,0-8.4-5.65-12.51-25.71-19.37-27.94-9.43-38.39-19.54-38.39-37.2,0-20,16.8-33.93,40.62-33.93,23.48,0,41.82,14.22,45.6,35.31l-24.69,5.31c-3.25-12.17-9.94-17.83-20.91-17.83-9.43,0-15.6,4.29-15.6,11,0,6.17,5.14,9.6,23,15.6,14.91,5.14,25.71,10.8,32.06,17.14s9.42,14.23,9.42,24c0,20.74-18,34.62-44.22,34.62-28.63,0-46.45-14.74-50.74-42.16Z"></path></g><g fill="#6a52ff"><path d="M127.12,10,109.92.11a.84.84,0,0,0-.84,0L91.67,10.16a.84.84,0,0,1-.84,0L73.42.11a.84.84,0,0,0-.84,0L55.38,10a.42.42,0,0,0,0,.73L91,31.36a.45.45,0,0,0,.42,0l35.66-20.59A.42.42,0,0,0,127.12,10Z"></path><path d="M163.62,31.11l-17.2-9.92a.84.84,0,0,0-.84,0L91.67,52.31a.84.84,0,0,1-.84,0L36.92,21.19a.84.84,0,0,0-.84,0l-17.2,9.92a.42.42,0,0,0,0,.73L91,73.5a.4.4,0,0,0,.42,0l72.16-41.66A.42.42,0,0,0,163.62,31.11Z"></path><path d="M109.5,84.65v19.86a.42.42,0,0,0,.63.36l72.16-41.66a.41.41,0,0,0,.21-.36V43.48a.84.84,0,0,0-1.26-.73L109.92,83.92A.84.84,0,0,0,109.5,84.65Z"></path><path d="M110.13,147l72.16-41.66a.44.44,0,0,0,.21-.37V85.62a.84.84,0,0,0-1.26-.73l-71.32,41.18a.83.83,0,0,0-.42.73v19.85A.42.42,0,0,0,110.13,147Z"></path><path d="M91.25,177.53V95.19a.83.83,0,0,0-.42-.73L74.26,84.89a.84.84,0,0,0-1.26.73V167a.84.84,0,0,1-1.26.73l-16.57-9.57a.84.84,0,0,1-.42-.73V74.11a.84.84,0,0,0-.42-.73L37.76,63.82a.84.84,0,0,0-1.26.73v81.37a.84.84,0,0,1-1.26.73l-16.57-9.56a.84.84,0,0,1-.42-.73V53a.84.84,0,0,0-.42-.73L1.26,42.75A.84.84,0,0,0,0,43.48V147.14a.41.41,0,0,0,.21.36L91,199.94a.4.4,0,0,0,.42,0l90.83-52.44a.41.41,0,0,0,.21-.36V127.77a.84.84,0,0,0-1.26-.73L92.51,178.26A.84.84,0,0,1,91.25,177.53Z"></path></g></svg></a>
                        </div>
                        <div class="col-md-8">
                            <h4 class="channels-text">Easily build scalable realtime graphs, geotracking, multiplayer games, and more in your web and mobile apps with our Analytics Integrations.</h4>
                        </div>
                    </div>
                    <div class="languages-tabs">
                        <nav>
                          <div class="nav nav-tabs clear-fix" id="nav-tab" role="tablist">
                            <a class="nav-item nav-link active" id="nav-php-tab" data-toggle="tab" href="#nav-php" role="tab" aria-controls="nav-php" aria-selected="true">PHP</a>
                            <a class="nav-item nav-link" id="nav-node-tab" data-toggle="tab" href="#nav-node" role="tab" aria-controls="nav-node" aria-selected="false">Node</a>
                            <a class="nav-item nav-link" id="nav-ruby-tab" data-toggle="tab" href="#nav-ruby" role="tab" aria-controls="nav-ruby" aria-selected="false">Ruby</a>
                            <a class="nav-item nav-link" id="nav-asp-tab" data-toggle="tab" href="#nav-asp" role="tab" aria-controls="nav-asp" aria-selected="false">ASP</a>
                            <a class="nav-item nav-link" id="nav-java-tab" data-toggle="tab" href="#nav-java" role="tab" aria-controls="nav-java" aria-selected="false">Java</a>
                            <a class="nav-item nav-link" id="nav-python-tab" data-toggle="tab" href="#nav-python" role="tab" aria-controls="nav-python" aria-selected="false">Python</a>
                            <a class="nav-item nav-link" id="nav-go-tab" data-toggle="tab" href="#nav-go" role="tab" aria-controls="nav-go" aria-selected="false">Go</a>
                          </div>
                        </nav>
                        <div class="tab-content" id="nav-tabContent">
                            <div class="tab-pane fade show active" id="nav-php" role="tabpanel" aria-labelledby="nav-php-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="nmbr4">4</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">pusher-&gt;trigger(<span class="hljs-string">'my-channel'</span>,
                                                <span class="hljs-string">'my-event'</span>, [<br>
                                                <span class="hljs-string">'message'</span> =&gt; <span class="hljs-string">'hello world'<br></span> ]);
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-node" role="tabpanel" aria-labelledby="nav-node-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="nmbr4">4</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">
                                                pusher.trigger(<span class="hljs-string">'my-channel'</span>, <span class="hljs-string">'my-event'</span>, {<br>
                                                <span class="hljs-string">"message"</span>: <span class="hljs-string">"hello world"</span><br>
                                                });
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-ruby" role="tabpanel" aria-labelledby="nav-ruby-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="nmbr4">4</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">pusher-&gt;trigger(<span class="hljs-string">'my-channel'</span>,
                                                <span class="hljs-string">'my-event'</span>, {<br>
                                                <span class="hljs-string">message</span> : <span class="hljs-string">'hello world'<br></span> })
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-asp" role="tabpanel" aria-labelledby="nav-asp-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="nmbr4">4</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">pusher-&gt;trigger(<span class="hljs-string">'my-channel'</span>,
                                                <span class="hljs-string">'my-event'</span>, <span class="hljs-keyword">new</span> {<br>
                                                <span class="hljs-string">message</span> = <span class="hljs-string">'hello world'<br></span> });
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-java" role="tabpanel" aria-labelledby="nav-java-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">pusher.trigger(<span class="hljs-string">"my-channel"</span>, <span class="hljs-string">"my-event"</span>, Collections.singletonMap(<span class="hljs-string">"message"</span>, <span class="hljs-string">"hello world"</span>));
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-python" role="tabpanel" aria-labelledby="nav-python-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="nmbr4">4</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">pusher.trigger(<span class="hljs-string">'my-channel'</span>,
                                                <span class="hljs-string">'my-event'</span>, {<br>
                                                <span class="hljs-string">'message'</span> : <span class="hljs-string">'hello world'<br></span> })
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="tab-pane fade" id="nav-go" role="tabpanel" aria-labelledby="nav-go-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="nmbr4">4</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">pusher.trigger(<span class="hljs-string">'my-channel'</span>,
                                                <span class="hljs-string">'my-event'</span>, <span class="hljs-keyword">map</span>[<span class="hljs-keyword">string</span>]<span class="hljs-keyword">string</span>{<br>
                                                <span class="hljs-string">'message'</span> : <span class="hljs-string">'hello world'<br></span> })
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="tab-content" id="nav-tabContent2">
                            <nav>
                              <div class="nav nav-tabs clear-fix" id="nav-tab2" role="tablist">
                                <a class="nav-item nav-link active" id="nav-js-tab" data-toggle="tab" href="#nav-js" role="tab" aria-controls="nav-js" aria-selected="true">JS</a>
                                <a class="nav-item nav-link" id="nav-android-tab" data-toggle="tab" href="#nav-android" role="tab" aria-controls="nav-android" aria-selected="false">Android</a>
                                <a class="nav-item nav-link" id="nav-iosS-tab" data-toggle="tab" href="#nav-iosS" role="tab" aria-controls="nav-iosS" aria-selected="false">IOS(Swift)</a>
                                <a class="nav-item nav-link" id="nav-iosO-tab" data-toggle="tab" href="#nav-iosO" role="tab" aria-controls="nav-iosO" aria-selected="false">IOS(Obj-c)</a>
                              </div>
                            </nav>
                            <div class="tab-pane fade show active" id="nav-js" role="tabpanel" aria-labelledby="nav-js-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="">4</span><br>
                                            <span class="nmbr4">5</span>
                                            <span class="nmbr4">6</span>
                                            <span class="nmbr4">7</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">
                                                <span class="hljs-keyword">var</span> channel = pusher.subscribe(<span class="hljs-string">'my-channel'</span>);<br>
                                                channel.bind(<span class="hljs-string">'my-event'</span>, <span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">data</span>) </span>{ <br>&nbsp;&nbsp;alert(<span class="hljs-string">'Received my-event with message: '</span> + data.message); <br>});
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-android" role="tabpanel" aria-labelledby="nav-android-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="">4</span><br>
                                            <span class="">5</span><br>
                                            <span class="">6</span><br>
                                            <span class="">7</span><br>
                                            <span class="nmbr4">8</span>
                                            <span class="nmbr4">9</span>
                                            <span class="nmbr4">10</span>
                                            <span class="nmbr4">11</span>
                                            <span class="nmbr4">12</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">
                                                Channel channel = pusher.subscribe(<span class="hljs-string">"my-channel"</span>); <br>
                                                channel.bind(<span class="hljs-string">"my-event"</span>, <span class="hljs-keyword">new</span> SubscriptionEventListener() {<br> <span class="hljs-meta">&nbsp;&nbsp;@Override</span><br>
                                                <span class="hljs-function">&nbsp;&nbsp;<span class="hljs-keyword">public</span> <span class="hljs-keyword">void</span> <span class="hljs-title">onEvent</span><span class="hljs-params">(String channel, String event, String data)</span> </span>{<br> &nbsp;&nbsp;&nbsp;System.put.println(<span class="hljs-string">"Received event with data: "</span> + data);<br> &nbsp;&nbsp;}<br>});
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-iosS" role="tabpanel" aria-labelledby="nav-iosS-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="">4</span><br>
                                            <span class="">5</span><br>
                                            <span class="">6</span><br>
                                            <span class="">7</span><br>
                                            <span class="nmbr4">8</span>
                                            <span class="nmbr4">9</span>
                                            <span class="nmbr4">10</span>
                                            <span class="nmbr4">11</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">
                                                <span class="hljs-keyword">let</span> channel = pusher.subscribe(<span class="hljs-string">"my-channel"</span>)<br><br>
                                                channel.bind(eventName: <span class="hljs-string">"my-event"</span>, callback: { (optionalData: <span class="hljs-type">Any</span>?) -&gt; <span class="hljs-type">Void</span> <span class="hljs-keyword">in</span><br> &nbsp;&nbsp;<span class="hljs-keyword">if</span> <span class="hljs-keyword">let</span> data = optionalData {<br> &nbsp;&nbsp;&nbsp;&nbsp;<span class="hljs-built_in">print</span>(<span class="hljs-string">"Received event with data: \(data)"</span>) <br> &nbsp;&nbsp;}<br>})
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="nav-iosO" role="tabpanel" aria-labelledby="nav-iosO-tab">
                                <div class="clear-fix">
                                    <div class="">
                                        <div class="side-line">
                                            <span class="">1</span><br>
                                            <span class="">2</span><br>
                                            <span class="">3</span><br>
                                            <span class="">4</span><br>
                                            <span class="">5</span><br>
                                            <span class="">6</span><br>
                                            <span class="nmbr4">7</span>
                                            <span class="nmbr4">8</span>
                                            <span class="nmbr4">9</span>
                                            <span class="nmbr4">10</span>
                                            <span class="nmbr4">11</span>
                                            <span class="nmbr4">12</span>
                                        </div>
                                    </div>
                                    <div class="">
                                        <div class="code-area">
                                            <div class="hljs">
                                                PusherChannel *channel = [pusher subscribeWithChannelName:<span class="hljs-string">@"my-channel"</span>];<br><br> [channel bindWithEventName:<span class="hljs-string">@"my-event"</span> callback:^<span class="hljs-keyword">void</span> (<span class="hljs-built_in">NSDictionary</span> *data) {<br> &nbsp;&nbsp;&nbsp;&nbsp;<span class="hljs-built_in">NSString</span> *message = data[<span class="hljs-string">@"message"</span>];<br> &nbsp;&nbsp;&nbsp;&nbsp;<span class="hljs-built_in">NSLog</span>(<span class="hljs-string">@"message received: %@"</span>, message);<br> }];
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bellow-area">
                        <div class="row">
                            <div class="col-md-6">
                                <ul class="bellow-area-ul">
                                    <li class="bellow-area-li">
                                        <img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/general/doublecheck.svg" alt="pic-logo" class="img-fluid">
                                        Adobe / Google Soultions.
                                    </li>
                                    <li class="bellow-area-li">
                                        <img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/general/doublecheck.svg" alt="pic-logo" class="img-fluid">
                                        Manage Marketing Pixels.
                                    </li>
                                    <li class="bellow-area-li">
                                        <img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/general/doublecheck.svg"alt="pic-logo" class="img-fluid">
                                        No Developers Needed.
                                    </li>
                                </ul>
                            </div>
                            <div class="col-md-6">
                                <div class="bellow-area-right">
                                    <a href="#" class="btn btn-explore">Explore Analytics</a><br>
                                    <a href="#" class="pricing-link">Pricing <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#00DE72" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
  </main>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
metaInfo: {
    title: 'Hello, world!',
    description: 'testinggjsfkghsdghfhjgjkshghlshglghjg'
  },
  methods: {
  }
}
</script>

<style>

.text-js{
	opacity: 1;
}

</style>
