---
title: VRDisplay.capabilities
slug: Web/API/VRDisplay/capabilities
tags:
  - API
  - Experimental
  - Property
  - Reference
  - VR
  - VRDisplay
  - Virtual Reality
  - WebVR
  - capabilities
browser-compat: api.VRDisplay.capabilities
---
<div>{{APIRef("WebVR API")}}{{Deprecated_Header}}</div>

<p>The <strong><code>capabilities</code></strong> read-only property of the {{domxref("VRDisplay")}} interface returns a {{domxref("VRDisplayCapabilities")}} object that indicates the various capabilities of the <code>VRDisplay</code>.</p>

<div class="notecard note">
  <p><strong>Note:</strong> This property was part of the old <a href="https://immersive-web.github.io/webvr/spec/1.1/">WebVR API</a>. It has been superseded by the <a href="https://immersive-web.github.io/webxr/">WebXR Device API</a>.</p>
</div>

<h2 id="Syntax">Syntax</h2>

<pre class="brush: js">var myCapabilities = vrDisplayInstance.capabilities;</pre>

<h3 id="Value">Value</h3>

<p>A {{domxref("VRDisplayCapabilities")}} object.</p>

<h2 id="Examples">Examples</h2>

<p>See <a href="/en-US/docs/Web/API/VRDisplayCapabilities#examples"><code>VRDisplayCapabilities</code></a> for example code.</p>

<h2 id="Specifications">Specifications</h2>

<p>This property was part of the old <a href="https://immersive-web.github.io/webvr/spec/1.1/">WebVR API</a> that has been superseded by the <a href="https://immersive-web.github.io/webxr/">WebXR Device API</a>. It is no longer on track to becoming a standard.</p>
<p>Until all browsers have implemented the new <a href="/en-US/docs/Web/API/WebXR_Device_API/Fundamentals">WebXR APIs</a>, it is recommended to rely on frameworks, like <a href="https://aframe.io/">A-Frame</a>, <a href="https://www.babylonjs.com/">Babylon.js</a>, or <a href="https://threejs.org/">Three.js</a>, or a <a href="https://github.com/immersive-web/webxr-polyfill">polyfill</a>, to develop WebXR applications that will work across all browsers <a href="https://developer.oculus.com/documentation/oculus-browser/browser-vr-xr/">[1]</a>.</p>

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>

<h2 id="See_also">See also</h2>

<ul>
 <li><a href="/en-US/docs/Web/API/WebVR_API">WebVR API homepage</a></li>
 <li><a href="https://mixedreality.mozilla.org/">https://mixedreality.mozilla.org/</a> — demos, downloads, and other resources from the Mozilla VR team.</li>
</ul>