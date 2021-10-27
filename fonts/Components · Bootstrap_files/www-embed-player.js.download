(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function t(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
t("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ha(a){if(!(a instanceof Array)){a=u(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ia="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ja=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ia(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ka;
if("function"==typeof Object.setPrototypeOf)ka=Object.setPrototypeOf;else{var la;a:{var ma={a:!0},na={};try{na.__proto__=ma;la=na.a;break a}catch(a){}la=!1}ka=la?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var oa=ka;
function v(a,b){a.prototype=ia(b.prototype);a.prototype.constructor=a;if(oa)oa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.O=b.prototype}
function pa(){this.A=!1;this.l=null;this.i=void 0;this.h=1;this.o=this.m=0;this.C=this.j=null}
function qa(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
pa.prototype.B=function(a){this.i=a};
function ra(a,b){a.j={Za:b,bb:!0};a.h=a.m||a.o}
pa.prototype.return=function(a){this.j={return:a};this.h=this.o};
function w(a,b,c){a.h=c;return{value:b}}
pa.prototype.u=function(a){this.h=a};
function sa(a,b,c){a.m=b;void 0!=c&&(a.o=c)}
function ta(a){a.m=0;var b=a.j.Za;a.j=null;return b}
function ua(a){a.C=[a.j];a.m=0;a.o=0}
function va(a){var b=a.C.splice(0)[0];(b=a.j=a.j||b)?b.bb?a.h=a.m||a.o:void 0!=b.u&&a.o<b.u?(a.h=b.u,a.j=null):a.h=a.o:a.h=0}
function wa(a){this.h=new pa;this.i=a}
function xa(a,b){qa(a.h);var c=a.h.l;if(c)return ya(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return za(a)}
function ya(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.A=!1,e;var f=e.value}catch(g){return a.h.l=null,ra(a.h,g),za(a)}a.h.l=null;d.call(a.h,f);return za(a)}
function za(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.A=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ra(a.h,c)}a.h.A=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.bb)throw b.Za;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ba(a){this.next=function(b){qa(a.h);a.h.l?b=ya(a,a.h.l.next,b,a.h.B):(a.h.B(b),b=za(a));return b};
this.throw=function(b){qa(a.h);a.h.l?b=ya(a,a.h.l["throw"],b,a.h.B):(ra(a.h,b),b=za(a));return b};
this.return=function(b){return xa(a,b)};
this[Symbol.iterator]=function(){return this}}
function x(a,b){b=new Ba(new wa(b));oa&&a.prototype&&oa(b,a.prototype);return b}
t("Reflect",function(a){return a?a:{}});
t("Reflect.construct",function(){return ja});
t("Reflect.setPrototypeOf",function(a){return a?a:oa?function(b,c){try{return oa(b,c),!0}catch(d){return!1}}:null});
function Ca(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
t("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Ca(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Ca(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Ca(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Ca(k,g)&&Ca(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Ca(k,g)&&Ca(k[g],this.h)?delete k[g][this.h]:!1};
return b});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return fa(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.data_[l];if(n&&Ca(h.data_,l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.entry),this.h.previous.next=l.entry,this.h.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ea(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ea(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
t("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ea(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
t("Object.setPrototypeOf",function(a){return a||oa});
var Fa="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Ca(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||Fa});
t("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.A=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.o()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.o=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.T),reject:g(this.o)}};
b.prototype.T=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ga(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.L(g):this.m(g)}};
b.prototype.L=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.ha(h,g):this.m(g)};
b.prototype.o=function(g){this.B(2,g)};
b.prototype.m=function(g){this.B(1,g)};
b.prototype.B=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.U();this.C()};
b.prototype.U=function(){var g=this;e(function(){if(g.J()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.J=function(){if(this.A)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.C=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ga=function(g){var h=this.l();g.ra(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,q){return"function"==typeof r?function(y){try{l(r(y))}catch(B){n(B)}}:q}
var l,n,p=new b(function(r,q){l=r;n=q});
this.ra(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.ra=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.A=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),n=l.next();!n.done;n=l.next())d(n.value).ra(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(y){return function(B){r[y]=B;q--;0==q&&l(r)}}
var r=[],q=0;do r.push(void 0),q++,d(k.value).ra(p(r.length-1),n),k=h.next();while(!k.done)})};
return b});
function Ga(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.entries",function(a){return a?a:function(){return Ga(this,function(b,c){return[b,c]})}});
t("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Ca(b,d)&&c.push([d,b[d]]);return c}});
t("Array.prototype.keys",function(a){return a?a:function(){return Ga(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return Ga(this,function(b,c){return c})}});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ea(this,b,"includes").indexOf(b,c||0)}});
t("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
t("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
t("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
t("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Ca(b,d)&&c.push(b[d]);return c}});
var z=this||self;function A(a,b,c){a=a.split(".");c=c||z;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function C(a,b){a=a.split(".");b=b||z;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ha(){}
function Ia(a){a.Ka=void 0;a.getInstance=function(){return a.Ka?a.Ka:a.Ka=new a}}
function Ja(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ka(a){var b=Ja(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function La(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ma(a){return Object.prototype.hasOwnProperty.call(a,Oa)&&a[Oa]||(a[Oa]=++Pa)}
var Oa="closure_uid_"+(1E9*Math.random()>>>0),Pa=0;function Qa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ra(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Sa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Sa=Qa:Sa=Ra;return Sa.apply(null,arguments)}
function Ta(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Ua(a,b){A(a,b,void 0)}
function D(a,b){function c(){}
c.prototype=b.prototype;a.O=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Gm=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Va(a){return a}
;function Wa(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Wa);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.rb=b)}
D(Wa,Error);Wa.prototype.name="CustomError";function Xa(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Ya(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Za=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},E=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},$a=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},ab=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},bb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
E(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function cb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function db(a,b){b=Za(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function eb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function fb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ka(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function gb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function hb(a){var b=ib,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function jb(a){for(var b in a)return!1;return!0}
function kb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function lb(){var a=F("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function mb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function nb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function ob(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=ob(a[c]);return b}
var pb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function qb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<pb.length;f++)c=pb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var rb;function sb(){if(void 0===rb){var a=null,b=z.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Va,createScript:Va,createScriptURL:Va})}catch(c){z.console&&z.console.error(c.message)}rb=a}else rb=a}return rb}
;function tb(a,b){this.h=a===ub&&b||""}
tb.prototype.X=!0;tb.prototype.W=function(){return this.h};
function vb(a){return new tb(ub,a)}
var ub={};vb("");var wb={};function xb(a){this.h=wb===wb?a:"";this.X=!0}
xb.prototype.W=function(){return this.h.toString()};
xb.prototype.toString=function(){return this.h.toString()};function yb(a,b){this.h=b===zb?a:""}
m=yb.prototype;m.X=!0;m.W=function(){return this.h.toString()};
m.Ja=!0;m.Fa=function(){return 1};
m.toString=function(){return this.h+""};
function Ab(a){if(a instanceof yb&&a.constructor===yb)return a.h;Ja(a);return"type_error:TrustedResourceUrl"}
var zb={};function Bb(a){var b=sb();a=b?b.createScriptURL(a):a;return new yb(a,zb)}
;var Cb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Db=/&/g,Eb=/</g,Fb=/>/g,Gb=/"/g,Hb=/'/g,Ib=/\x00/g,Jb=/[\x00&<>"']/;function Kb(a,b){this.h=b===Lb?a:""}
m=Kb.prototype;m.X=!0;m.W=function(){return this.h.toString()};
m.Ja=!0;m.Fa=function(){return 1};
m.toString=function(){return this.h.toString()};
function Nb(a){if(a instanceof Kb&&a.constructor===Kb)return a.h;Ja(a);return"type_error:SafeUrl"}
var Ob=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),Pb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Qb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Lb={},Rb=new Kb("about:invalid#zClosurez",Lb);var Sb;a:{var Tb=z.navigator;if(Tb){var Ub=Tb.userAgent;if(Ub){Sb=Ub;break a}}Sb=""}function H(a){return-1!=Sb.indexOf(a)}
;function Vb(){return H("Firefox")||H("FxiOS")}
function Wb(){return(H("Chrome")||H("CriOS"))&&!H("Edge")}
;var Xb={};function Yb(a,b,c){this.h=c===Xb?a:"";this.i=b;this.X=this.Ja=!0}
Yb.prototype.Fa=function(){return this.i};
Yb.prototype.W=function(){return this.h.toString()};
Yb.prototype.toString=function(){return this.h.toString()};
function Zb(a,b){var c=sb();a=c?c.createHTML(a):a;return new Yb(a,b,Xb)}
;function $b(a,b){b instanceof Kb||b instanceof Kb||(b="object"==typeof b&&b.X?b.W():String(b),Qb.test(b)||(b="about:invalid#zClosurez"),b=new Kb(b,Lb));a.href=Nb(b)}
function ac(a,b){a.rel="stylesheet";a.href=Ab(b).toString();(b=bc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function cc(){return bc("script[nonce]",void 0)}
var dc=/^[\w+/_-]+[=]{0,2}$/;function bc(a,b){b=(b||z).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&dc.test(a)?a:"":""}
;function ec(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var fc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function gc(a){return a?decodeURI(a):a}
function hc(a){return gc(a.match(fc)[3]||null)}
function ic(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)ic(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function jc(a){var b=[],c;for(c in a)ic(c,a[c],b);return b.join("&")}
function kc(a,b){b=jc(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var lc=/#|$/;function I(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function mc(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;function nc(a){nc[" "](a);return a}
nc[" "]=Ha;var oc=H("Opera"),pc=H("Trident")||H("MSIE"),qc=H("Edge"),rc=H("Gecko")&&!(-1!=Sb.toLowerCase().indexOf("webkit")&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),sc=-1!=Sb.toLowerCase().indexOf("webkit")&&!H("Edge"),tc=H("Android");function uc(){var a=z.document;return a?a.documentMode:void 0}
var vc;a:{var wc="",xc=function(){var a=Sb;if(rc)return/rv:([^\);]+)(\)|;)/.exec(a);if(qc)return/Edge\/([\d\.]+)/.exec(a);if(pc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(sc)return/WebKit\/(\S+)/.exec(a);if(oc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
xc&&(wc=xc?xc[1]:"");if(pc){var yc=uc();if(null!=yc&&yc>parseFloat(wc)){vc=String(yc);break a}}vc=wc}var zc=vc,Ac;if(z.document&&pc){var Bc=uc();Ac=Bc?Bc:parseInt(zc,10)||void 0}else Ac=void 0;var Cc=Ac;Vb();var Dc=mc()||H("iPod"),Ec=H("iPad");!H("Android")||Wb()||Vb();Wb();var Fc=H("Safari")&&!(Wb()||H("Coast")||H("Opera")||H("Edge")||H("Edg/")||H("OPR")||Vb()||H("Silk")||H("Android"))&&!(mc()||H("iPad")||H("iPod"));var Gc={},Hc=null;
function Ic(a,b){Ka(a);void 0===b&&(b=0);if(!Hc){Hc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Gc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Hc[h]&&(Hc[h]=g)}}}b=Gc[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Jc="function"===typeof Uint8Array;function Kc(a){return null!==a&&"object"==typeof a&&!Array.isArray(a)&&!Lc(a)}
function Mc(a,b){if(null!=a)return Array.isArray(a)||Kc(a)?Nc(a,b):b(a)}
function Nc(a,b){if(Array.isArray(a)){for(var c=Array(a.length),d=0;d<a.length;d++)c[d]=Mc(a[d],b);Array.isArray(a)&&a.Fb&&Oc(c);return c}c={};for(d in a)c[d]=Mc(a[d],b);return c}
function Pc(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":return Lc(a)?Ic(a):a;default:return a}}
function Qc(a){return Lc(a)?new Uint8Array(a):a}
var Rc={Fb:{value:!0,configurable:!0}};function Oc(a){Array.isArray(a)&&!Object.isFrozen(a)&&Object.defineProperties(a,Rc);return a}
function Lc(a){return Jc&&null!=a&&a instanceof Uint8Array}
;function Sc(a,b){this.h=a;this.i=b;this.map={};this.j=!0;if(0<this.h.length){for(a=0;a<this.h.length;a++){b=this.h[a];var c=b[0];this.map[c.toString()]=new Tc(c,b[1])}this.j=!0}}
m=Sc.prototype;m.isFrozen=function(){return!1};
m.toJSON=function(){var a=this.P(!1);return Nc(a,Pc)};
m.P=function(a){if(this.j){if(this.i){var b=this.map,c;for(c in b)if(Object.prototype.hasOwnProperty.call(b,c)){var d=b[c].h;d&&d.P(a)}}}else{this.h.length=0;b=Uc(this);b.sort();for(c=0;c<b.length;c++){d=this.map[b[c]];var e=d.h;e&&e.P(a);this.h.push([d.key,d.value])}this.j=!0}return this.h};
m.clear=function(){this.map={};this.j=!1};
m.entries=function(){var a=[],b=Uc(this);b.sort();for(var c=0;c<b.length;c++){var d=this.map[b[c]];a.push([d.key,Vc(this,d)])}return new Wc(a)};
m.keys=function(){var a=[],b=Uc(this);b.sort();for(var c=0;c<b.length;c++)a.push(this.map[b[c]].key);return new Wc(a)};
m.values=function(){var a=[],b=Uc(this);b.sort();for(var c=0;c<b.length;c++)a.push(Vc(this,this.map[b[c]]));return new Wc(a)};
m.forEach=function(a,b){var c=Uc(this);c.sort();for(var d=0;d<c.length;d++){var e=this.map[c[d]];a.call(b,Vc(this,e),e.key,this)}};
m.set=function(a,b){var c=new Tc(a);this.i?(c.h=b,c.value=b.P(!1)):c.value=b;this.map[a.toString()]=c;this.j=!1;return this};
function Vc(a,b){return a.i?(b.h||(b.h=new a.i(b.value),a.isFrozen()&&null(b.h)),b.h):b.value}
m.get=function(a){if(a=this.map[a.toString()])return Vc(this,a)};
m.has=function(a){return a.toString()in this.map};
function Uc(a){a=a.map;var b=[],c;for(c in a)Object.prototype.hasOwnProperty.call(a,c)&&b.push(c);return b}
Sc.prototype[Symbol.iterator]=function(){return this.entries()};
function Tc(a,b){this.key=a;this.value=b;this.h=void 0}
function Wc(a){this.i=0;this.h=a}
Wc.prototype.next=function(){return this.i<this.h.length?{done:!1,value:this.h[this.i++]}:{done:!0,value:void 0}};
Wc.prototype[Symbol.iterator]=function(){return this};var Xc;function Yc(a,b,c){var d=Xc;Xc=null;a||(a=d);d=this.constructor.Km;a||(a=d?[d]:[]);this.l=d?0:-1;this.h=null;this.i=a;a:{d=this.i.length;a=d-1;if(d&&(d=this.i[a],Kc(d))){this.o=a-this.l;this.j=d;break a}void 0!==b&&-1<b?(this.o=Math.max(b,a+1-this.l),this.j=null):this.o=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)a=c[b],a<this.o?(a+=this.l,(d=this.i[a])?Oc(d):this.i[a]=Zc):($c(this),(d=this.j[a])?Oc(d):this.j[a]=Zc)}
var Zc=Object.freeze(Oc([]));function $c(a){var b=a.o+a.l;a.i[b]||(a.j=a.i[b]={})}
function ad(a,b,c){return-1===b?null:(void 0===c?0:c)||b>=a.o?a.j?a.j[b]:void 0:a.i[b+a.l]}
function bd(a,b,c){a.h||(a.h={});if(b in a.h)return a.h[b];var d=ad(a,b);d||(d=Oc([]),cd(a,b,d));c=new Sc(d,c);return a.h[b]=c}
function cd(a,b,c,d){(void 0===d?0:d)||b>=a.o?($c(a),a.j[b]=c):a.i[b+a.l]=c}
function dd(a,b,c,d){if(-1===c)return null;a.h||(a.h={});a.h[c]||(d=ad(a,c,void 0===d?!1:d))&&(a.h[c]=new b(d));return a.h[c]}
function ed(a,b,c){a.h||(a.h={});var d=a.h[c];if(!d){var e=void 0===e?!1:e;d=ad(a,c,e);null==d&&(d=Zc);d===Zc&&(d=Oc([]),cd(a,c,d,e));e=d;d=[];for(var f=0;f<e.length;f++)d[f]=new b(e[f]);a.h[c]=d}return d}
Yc.prototype.toJSON=function(){var a=this.P(!1);return Nc(a,Pc)};
Yc.prototype.P=function(a){if(this.h)for(var b in this.h){var c=this.h[b];if(Array.isArray(c))for(var d=0;d<c.length;d++)c[d]&&c[d].P(a);else c&&c.P(a)}return this.i};
Yc.prototype.toString=function(){return this.P(!1).toString()};
Yc.prototype.clone=function(){var a=this.constructor,b=Nc(this.P(!1),Qc);Xc=b;a=new a(b);Xc=null;fd(a,this);return a};
function fd(a,b){b.m&&(a.m=b.m.slice());var c=b.h;if(c){b=b.j;var d={},e;for(e in c){var f=c[e];if(f){var g=!(!b||!b[e]),h=+e;if(Array.isArray(f)){if(f.length)for(g=ed(a,f[0].constructor,h),h=0;h<Math.min(g.length,f.length);h++)fd(g[h],f[h])}else f instanceof Sc?f.i&&(d.Ba=bd(a,h,f.i),f.forEach(function(k){return function(l,n){return fd(k.Ba.get(n),l)}}(d))):(g=dd(a,f.constructor,h,g))&&fd(g,f)}d={Ba:d.Ba}}}}
;var gd=window;vb("csi.gstatic.com");vb("googleads.g.doubleclick.net");vb("pagead2.googlesyndication.com");vb("partner.googleadservices.com");vb("pubads.g.doubleclick.net");vb("securepubads.g.doubleclick.net");vb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var hd={};function id(){}
function jd(a){this.h=a}
v(jd,id);jd.prototype.toString=function(){return this.h};
var kd=new jd("about:invalid#zTSz",hd);function ld(a){this.isValid=a}
function md(a){return new ld(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var nd=[md("data"),md("http"),md("https"),md("mailto"),md("ftp"),new ld(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function od(a){if(a instanceof id)if(a instanceof jd)a=a.h;else throw Error("");else a=Nb(a);return a}
;function pd(a,b){a.src=Ab(b);var c;b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document;var d=null===(c=b.querySelector)||void 0===c?void 0:c.call(b,"script[nonce]");(c=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function qd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=qd.prototype;m.clone=function(){return new qd(this.x,this.y)};
m.equals=function(a){return a instanceof qd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function rd(a,b){this.width=a;this.height=b}
m=rd.prototype;m.clone=function(){return new rd(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function sd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function td(a,b){gb(b,function(c,d){c&&"object"==typeof c&&c.X&&(c=c.W());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:ud.hasOwnProperty(d)?a.setAttribute(ud[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var ud={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function vd(a,b,c){var d=arguments,e=document,f=d[1],g=wd(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):td(g,f));2<d.length&&xd(e,g,d);return g}
function xd(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Ka(f)||La(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(La(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}E(g?eb(f):f,d)}}}
function wd(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function yd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function zd(a){var b=Ad;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Bd(){var a=[];zd(function(b){a.push(b)});
return a}
var Ad={lc:"allow-forms",mc:"allow-modals",nc:"allow-orientation-lock",oc:"allow-pointer-lock",pc:"allow-popups",qc:"allow-popups-to-escape-sandbox",sc:"allow-presentation",tc:"allow-same-origin",uc:"allow-scripts",wc:"allow-top-navigation",xc:"allow-top-navigation-by-user-activation"},Cd=Ya(function(){return Bd()});
function Dd(){var a=Ed(),b={};E(Cd(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Ed(){var a=void 0===a?document:a;var b="IFRAME";"application/xhtml+xml"===(null==a?void 0:a.contentType)&&(b=b.toLowerCase());return a.createElement(b)}
;function Fd(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Gd=(new Date).getTime();function Hd(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Id(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var r=g,q=0;64>q;q+=4)r[q/4]=p[q]<<24|p[q+1]<<16|p[q+2]<<8|p[q+3];for(q=16;80>q;q++)p=r[q-3]^r[q-8]^r[q-14]^r[q-16],r[q]=(p<<1|p>>>31)&4294967295;p=e[0];var y=e[1],B=e[2],G=e[3],R=e[4];for(q=0;80>q;q++){if(40>q)if(20>q){var P=G^y&(B^G);var K=1518500249}else P=y^B^G,K=1859775393;else 60>q?(P=y&B|G&(y|B),K=2400959708):(P=y^B^G,K=3395469782);P=((p<<5|p>>>27)&4294967295)+P+R+K+r[q]&4294967295;R=G;G=B;B=(y<<30|y>>>2)&4294967295;y=p;p=P}e[0]=e[0]+p&4294967295;e[1]=e[1]+y&4294967295;e[2]=
e[2]+B&4294967295;e[3]=e[3]+G&4294967295;e[4]=e[4]+R&4294967295}
function c(p,r){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var q=[],y=0,B=p.length;y<B;++y)q.push(p.charCodeAt(y));p=q}r||(r=p.length);q=0;if(0==l)for(;q+64<r;)b(p.slice(q,q+64)),q+=64,n+=64;for(;q<r;)if(f[l++]=p[q++],n++,64==l)for(l=0,b(f);q+64<r;)b(p.slice(q,q+64)),q+=64,n+=64}
function d(){var p=[],r=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var q=63;56<=q;q--)f[q]=r&255,r>>>=8;b(f);for(q=r=0;5>q;q++)for(var y=24;0<=y;y-=8)p[r++]=e[q]>>y&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,tb:function(){for(var p=d(),r="",q=0;q<p.length;q++)r+="0123456789ABCDEF".charAt(Math.floor(p[q]/16))+"0123456789ABCDEF".charAt(p[q]%16);return r}}}
;function Jd(a,b,c){var d=String(z.location.href);return d&&a&&b?[b,Kd(Hd(d),a,c||null)].join(" "):null}
function Kd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],E(d,function(h){e.push(h)}),Ld(e.join(" "));
var f=[],g=[];E(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];E(d,function(h){e.push(h)});
a=Ld(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Ld(a){var b=Id();b.update(a);return b.tb().toLowerCase()}
;var Md={};function Nd(a){this.h=a||{cookie:""}}
m=Nd.prototype;m.isEnabled=function(){if(!z.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{La:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Pm;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.La}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Cb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{La:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=Cb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Od=new Nd("undefined"==typeof document?null:document);function Pd(a){return!!Md.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Qd(a){a=void 0===a?!1:a;var b=z.__SAPISID||z.__APISID||z.__3PSAPISID||z.__OVERRIDE_SID;Pd(a)&&(b=b||z.__1PSAPISID);if(b)return!0;var c=new Nd(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");Pd(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Rd(a,b,c,d){(a=z[a])||(a=(new Nd(document)).get(b));return a?Jd(a,c,d):null}
function Sd(a){var b=void 0===b?!1:b;var c=Hd(String(z.location.href)),d=[];if(Qd(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?z.__SAPISID:z.__APISID;e||(e=new Nd(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Jd(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Pd(b)&&((b=Rd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Rd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Td(){this.data_=[];this.h=-1}
Td.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Td.prototype.get=function(a){return!!this.data_[a]};
function Ud(a){-1==a.h&&(a.h=bb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Vd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Vd.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Wd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Xd;
function Yd(){var a=z.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=wd(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Sa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!H("Trident")&&!H("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Va;c.Va=null;e()}};
return function(e){d.next={Va:e};d=d.next;b.port2.postMessage(0)}}return function(e){z.setTimeout(e,0)}}
;function Zd(a){z.setTimeout(function(){throw a;},0)}
;function $d(){this.i=this.h=null}
$d.prototype.add=function(a,b){var c=ae.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
$d.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var ae=new Vd(function(){return new be},function(a){return a.reset()});
function be(){this.next=this.scope=this.h=null}
be.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
be.prototype.reset=function(){this.next=this.scope=this.h=null};function ce(a,b){de||ee();fe||(de(),fe=!0);ge.add(a,b)}
var de;function ee(){if(z.Promise&&z.Promise.resolve){var a=z.Promise.resolve(void 0);de=function(){a.then(he)}}else de=function(){var b=he;
"function"!==typeof z.setImmediate||z.Window&&z.Window.prototype&&!H("Edge")&&z.Window.prototype.setImmediate==z.setImmediate?(Xd||(Xd=Yd()),Xd(b)):z.setImmediate(b)}}
var fe=!1,ge=new $d;function he(){for(var a;a=ge.remove();){try{a.h.call(a.scope)}catch(b){Zd(b)}Wd(ae,a)}fe=!1}
;function ie(a,b){this.h=a[z.Symbol.iterator]();this.i=b;this.j=0}
ie.prototype[Symbol.iterator]=function(){return this};
ie.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function je(a,b){return new ie(a,b)}
;function ke(){this.blockSize=-1}
;function le(){this.blockSize=-1;this.blockSize=64;this.h=[];this.o=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
D(le,ke);le.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function me(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
le.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.i;d<b;){if(0==f)for(;d<=c;)me(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){me(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){me(this,e);f=0;break}}this.i=f;this.l+=b}};
le.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;me(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function ne(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||z.$googDebugFname||b}catch(g){e="Not available",c=!0}b=oe(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,pe[c])c=pe[c];else{c=String(c);if(!pe[c]){var f=/function\s+([^\(]+)/m.exec(c);pe[c]=f?f[1]:"[Anonymous]"}c=pe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function oe(a,b){b||(b={});b[qe(a)]=!0;var c=a.stack||"";(a=a.rb)&&!b[qe(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=oe(a,b));return c}
function qe(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var pe={};function re(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function se(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ka(d)?se.apply(null,d):re(d)}}
;function J(){this.h=this.h;this.o=this.o}
J.prototype.h=!1;J.prototype.dispose=function(){this.h||(this.h=!0,this.D())};
function te(a,b){a.h?b():(a.o||(a.o=[]),a.o.push(b))}
J.prototype.D=function(){if(this.o)for(;this.o.length;)this.o.shift()()};function ue(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function ve(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function we(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:ue(a).match(/\S+/g)||[],b=0<=Za(a,b));return b}
function xe(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):we(a,"inverted-hdpi")&&ve(a,Array.prototype.filter.call(a.classList?a.classList:ue(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var ye="StopIteration"in z?z.StopIteration:{message:"StopIteration",stack:""};function ze(){}
ze.prototype.R=function(){throw ye;};
ze.prototype.next=function(){return Ae};
var Ae={done:!0,value:void 0};ze.prototype.M=function(){return this};function Be(a){if(a instanceof Ce||a instanceof De||a instanceof Ee)return a;if("function"==typeof a.R)return new Ce(function(){return Fe(a)});
if("function"==typeof a[Symbol.iterator])return new Ce(function(){return a[Symbol.iterator]()});
if("function"==typeof a.M)return new Ce(function(){return Fe(a.M())});
throw Error("Not an iterator or iterable.");}
function Fe(a){if(!(a instanceof ze))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.R();break}catch(d){if(d!==ye)throw d;b=!0}return{value:c,done:b}}}}
function Ce(a){this.i=a}
Ce.prototype.M=function(){return new De(this.i())};
Ce.prototype[Symbol.iterator]=function(){return new Ee(this.i())};
Ce.prototype.h=function(){return new Ee(this.i())};
function De(a){this.i=a}
v(De,ze);De.prototype.R=function(){var a=this.i.next();if(a.done)throw ye;return a.value};
De.prototype[Symbol.iterator]=function(){return new Ee(this.i)};
De.prototype.h=function(){return new Ee(this.i)};
function Ee(a){Ce.call(this,function(){return a});
this.j=a}
v(Ee,Ce);Ee.prototype.next=function(){return this.j.next()};function Ge(a,b){this.i={};this.h=[];this.ca=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Ge)for(c=He(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function He(a){Ie(a);return a.h.concat()}
m=Ge.prototype;m.has=function(a){return Je(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Ke;Ie(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Ke(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.ca=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return Je(this.i,a)?(delete this.i[a],--this.size,this.ca++,this.h.length>2*this.size&&Ie(this),!0):!1};
function Ie(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Je(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Je(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return Je(this.i,a)?this.i[a]:b};
m.set=function(a,b){Je(this.i,a)||(this.size+=1,this.h.push(a),this.ca++);this.i[a]=b};
m.forEach=function(a,b){for(var c=He(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new Ge(this)};
m.keys=function(){return Be(this.M(!0)).h()};
m.values=function(){return Be(this.M(!1)).h()};
m.entries=function(){var a=this;return je(this.keys(),function(b){return[b,a.get(b)]})};
m.M=function(a){Ie(this);var b=0,c=this.ca,d=this,e=new ze;e.R=function(){if(c!=d.ca)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)throw ye;var f=d.h[b++];return a?f:d.i[f]};
return e};
function Je(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function Le(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Le.prototype.stopPropagation=function(){this.j=!0};
Le.prototype.preventDefault=function(){this.defaultPrevented=!0};var Me=function(){if(!z.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{z.addEventListener("test",Ha,b),z.removeEventListener("test",Ha,b)}catch(c){}return a}();function Ne(a,b){Le.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
D(Ne,Le);var Oe={2:"touch",3:"pen",4:"mouse"};
Ne.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(rc){a:{try{nc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Oe[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Ne.O.preventDefault.call(this)};
Ne.prototype.stopPropagation=function(){Ne.O.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Ne.prototype.preventDefault=function(){Ne.O.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Pe="closure_listenable_"+(1E6*Math.random()|0);var Qe=0;function Re(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.wa=e;this.key=++Qe;this.la=this.qa=!1}
function Se(a){a.la=!0;a.listener=null;a.proxy=null;a.src=null;a.wa=null}
;function Te(a){this.src=a;this.listeners={};this.h=0}
Te.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Ue(a,b,d,e);-1<g?(b=a[g],c||(b.qa=!1)):(b=new Re(b,this.src,f,!!d,e),b.qa=c,a.push(b));return b};
Te.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Ue(e,b,c,d);return-1<b?(Se(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Ve(a,b){var c=b.type;c in a.listeners&&db(a.listeners[c],b)&&(Se(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Ue(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.la&&f.listener==b&&f.capture==!!c&&f.wa==d)return e}return-1}
;var We="closure_lm_"+(1E6*Math.random()|0),Xe={},Ye=0;function Ze(a,b,c,d,e){if(d&&d.once)$e(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Ze(a,b[f],c,d,e);else c=af(c),a&&a[Pe]?a.Y(b,c,La(d)?!!d.capture:!!d,e):bf(a,b,c,!1,d,e)}
function bf(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=La(e)?!!e.capture:!!e,h=cf(a);h||(a[We]=h=new Te(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=df();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Me||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(ef(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Ye++}}
function df(){function a(c){return b.call(a.src,a.listener,c)}
var b=ff;return a}
function $e(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)$e(a,b[f],c,d,e);else c=af(c),a&&a[Pe]?a.i.add(String(b),c,!0,La(d)?!!d.capture:!!d,e):bf(a,b,c,!0,d,e)}
function gf(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)gf(a,b[f],c,d,e);else(d=La(d)?!!d.capture:!!d,c=af(c),a&&a[Pe])?a.i.remove(String(b),c,d,e):a&&(a=cf(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Ue(b,c,d,e)),(c=-1<a?b[a]:null)&&hf(c))}
function hf(a){if("number"!==typeof a&&a&&!a.la){var b=a.src;if(b&&b[Pe])Ve(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(ef(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Ye--;(c=cf(b))?(Ve(c,a),0==c.h&&(c.src=null,b[We]=null)):Se(a)}}}
function ef(a){return a in Xe?Xe[a]:Xe[a]="on"+a}
function ff(a,b){if(a.la)a=!0;else{b=new Ne(b,this);var c=a.listener,d=a.wa||a.src;a.qa&&hf(a);a=c.call(d,b)}return a}
function cf(a){a=a[We];return a instanceof Te?a:null}
var jf="__closure_events_fn_"+(1E9*Math.random()>>>0);function af(a){if("function"===typeof a)return a;a[jf]||(a[jf]=function(b){return a.handleEvent(b)});
return a[jf]}
;function kf(){J.call(this);this.i=new Te(this);this.L=this;this.A=null}
D(kf,J);kf.prototype[Pe]=!0;kf.prototype.addEventListener=function(a,b,c,d){Ze(this,a,b,c,d)};
kf.prototype.removeEventListener=function(a,b,c,d){gf(this,a,b,c,d)};
function lf(a,b){var c=a.A;if(c){var d=[];for(var e=1;c;c=c.A)d.push(c),++e}a=a.L;c=b.type||b;"string"===typeof b?b=new Le(b,a):b instanceof Le?b.target=b.target||a:(e=b,b=new Le(c,a),qb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=mf(g,c,!0,b)&&e}b.j||(g=b.h=a,e=mf(g,c,!0,b)&&e,b.j||(e=mf(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=mf(g,c,!1,b)&&e}
kf.prototype.D=function(){kf.O.D.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Se(d[e]);delete a.listeners[c];a.h--}}this.A=null};
kf.prototype.Y=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function mf(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.la&&g.capture==c){var h=g.listener,k=g.wa||g.src;g.qa&&Ve(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function nf(a){of();return Bb(a)}
var of=Ha;function pf(a){var b=[];qf(new rf,a,b);return b.join("")}
function rf(){}
function qf(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),qf(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),sf(d,c),c.push(":"),qf(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":sf(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var tf={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},uf=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function sf(a,b){b.push('"',a.replace(uf,function(c){var d=tf[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),tf[c]=d);return d}),'"')}
;function vf(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function wf(a){this.h=0;this.A=void 0;this.l=this.i=this.j=null;this.o=this.m=!1;if(a!=Ha)try{var b=this;a.call(void 0,function(c){xf(b,2,c)},function(c){xf(b,3,c)})}catch(c){xf(this,3,c)}}
function yf(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
yf.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var zf=new Vd(function(){return new yf},function(a){a.reset()});
function Af(a,b,c){var d=zf.get();d.i=a;d.onRejected=b;d.context=c;return d}
function Bf(a){return new wf(function(b,c){c(a)})}
wf.prototype.then=function(a,b,c){return Cf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
wf.prototype.$goog_Thenable=!0;function Df(a,b){return Cf(a,null,b,void 0)}
wf.prototype.cancel=function(a){if(0==this.h){var b=new Ff(a);ce(function(){Gf(this,b)},this)}};
function Gf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Gf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Hf(c),If(c,e,3,b)))}a.j=null}else xf(a,3,b)}
function Jf(a,b){a.i||2!=a.h&&3!=a.h||Kf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Cf(a,b,c,d){var e=Af(null,null,null);e.h=new wf(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Ff?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Jf(a,e);return e.h}
wf.prototype.C=function(a){this.h=0;xf(this,2,a)};
wf.prototype.J=function(a){this.h=0;xf(this,3,a)};
function xf(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.C,f=a.J;if(d instanceof wf){Jf(d,Af(e||Ha,f||null,a));var g=!0}else if(vf(d))d.then(e,f,a),g=!0;else{if(La(d))try{var h=d.then;if("function"===typeof h){Lf(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.A=c,a.h=b,a.j=null,Kf(a),3!=b||c instanceof Ff||Mf(a,c))}}
function Lf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Kf(a){a.m||(a.m=!0,ce(a.B,a))}
function Hf(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
wf.prototype.B=function(){for(var a;a=Hf(this);)If(this,a,this.h,this.A);this.m=!1};
function If(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.o;a=a.j)a.o=!1;if(b.h)b.h.j=null,Nf(b,c,d);else try{b.j?b.i.call(b.context):Nf(b,c,d)}catch(e){Of.call(null,e)}Wd(zf,b)}
function Nf(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Mf(a,b){a.o=!0;ce(function(){a.o&&Of.call(null,b)})}
var Of=Zd;function Ff(a){Wa.call(this,a)}
D(Ff,Wa);Ff.prototype.name="cancel";function L(a){J.call(this);this.A=1;this.l=[];this.m=0;this.i=[];this.j={};this.B=!!a}
D(L,J);m=L.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.A;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.A=e+3;d.push(e);return e};
function Pf(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.ka(b)}}
m.ka=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ha):(c&&db(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.da=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.B)for(e=0;e<c.length;e++){var g=c[e];Qf(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h;e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.ka(c)}}return 0!=e}return!1};
function Qf(a,b,c){ce(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.ka,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.D=function(){L.O.D.call(this);this.clear();this.l.length=0};function Rf(a){this.h=a}
Rf.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,pf(b))};
Rf.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Rf.prototype.remove=function(a){this.h.remove(a)};function Sf(a){this.h=a}
D(Sf,Rf);function Tf(a){this.data=a}
function Uf(a){return void 0===a||a instanceof Tf?a:new Tf(a)}
Sf.prototype.set=function(a,b){Sf.O.set.call(this,a,Uf(b))};
Sf.prototype.i=function(a){a=Sf.O.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Sf.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Vf(a){this.h=a}
D(Vf,Sf);Vf.prototype.set=function(a,b,c){if(b=Uf(b)){if(c){if(c<Date.now()){Vf.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Vf.O.set.call(this,a,b)};
Vf.prototype.i=function(a){var b=Vf.O.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Vf.prototype.remove.call(this,a);else return b}};function Wf(){}
;function Xf(){}
D(Xf,Wf);Xf.prototype[Symbol.iterator]=function(){return Be(this.M(!0)).h()};
Xf.prototype.clear=function(){var a=Array.from(this);a=u(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Yf(a){this.h=a}
D(Yf,Xf);m=Yf.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.M=function(a){var b=0,c=this.h,d=new ze;d.R=function(){if(b>=c.length)throw ye;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function Zf(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
D(Zf,Yf);function $f(a,b){this.i=a;this.h=null;var c;if(c=pc)c=!(9<=Number(Cc));if(c){ag||(ag=new Ge);this.h=ag.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),ag.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
D($f,Xf);var bg={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},ag=null;function cg(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return bg[b]})}
m=$f.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(cg(a),b);dg(this)};
m.get=function(a){a=this.h.getAttribute(cg(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(cg(a));dg(this)};
m.M=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new ze;d.R=function(){if(b>=c.length)throw ye;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);dg(this)};
function dg(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function eg(a,b){this.i=a;this.h=b+"::"}
D(eg,Xf);eg.prototype.set=function(a,b){this.i.set(this.h+a,b)};
eg.prototype.get=function(a){return this.i.get(this.h+a)};
eg.prototype.remove=function(a){this.i.remove(this.h+a)};
eg.prototype.M=function(a){var b=this.i.M(!0),c=this,d=new ze;d.R=function(){for(var e=b.R();e.substr(0,c.h.length)!=c.h;)e=b.R();return a?e.substr(c.h.length):c.i.get(e)};
return d};function fg(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;function gg(a){Yc.call(this,a)}
v(gg,Yc);var hg,ig,jg,kg=z.window,lg=(null===(hg=null===kg||void 0===kg?void 0:kg.yt)||void 0===hg?void 0:hg.config_)||(null===(ig=null===kg||void 0===kg?void 0:kg.ytcfg)||void 0===ig?void 0:ig.data_)||{},mg=(null===(jg=null===kg||void 0===kg?void 0:kg.ytcfg)||void 0===jg?void 0:jg.obfuscatedData_)||[];new gg(mg);A("yt.config_",lg,void 0);A("yt.configJspb_",mg,void 0);function M(a){for(var b=0;b<arguments.length;++b);fg(lg,arguments)}
function F(a,b){return a in lg?lg[a]:b}
;var ng=[];function og(a){ng.forEach(function(b){return b(a)})}
function pg(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){qg(b)}}:a}
function qg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=F("ERRORS",[]),e.push([a,"ERROR",b,c,d]),M("ERRORS",e));og(a)}
function rg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=F("ERRORS",[]),e.push([a,"WARNING",b,c,d]),M("ERRORS",e))}
;var sg=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",sg,void 0);function tg(a){fg(sg,arguments)}
;function N(a){a=ug(a);return"string"===typeof a&&"false"===a?!1:!!a}
function vg(a,b){a=ug(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function ug(a){var b=F("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:F("EXPERIMENT_FLAGS",{})[a]}
;var wg={appSettingsCaptured:!0,foregroundHeartbeat:!0,foregroundHeartbeatScreenAssociated:!0,screenCreated:!0,visualElementAttached:!0,visualElementGestured:!0,visualElementHidden:!0,visualElementShown:!0,flowEvent:!0,visualElementStateChanged:!0,playbackAssociated:!0,youThere:!0,accountStateChangeSignedIn:!0,accountStateChangeSignedOut:!0},xg={latencyActionBaselined:!0,latencyActionInfo:!0,latencyActionTicked:!0,bedrockRepetitiveActionTimed:!0,adsClientStateChange:!0,streamzIncremented:!0,mdxDialAdditionalDataUpdateEvent:!0,
tvhtml5WatchKeyEvent:!0,tvhtml5VideoSeek:!0,tokenRefreshEvent:!0,adNotify:!0,adNotifyFilled:!0,tvhtml5LaunchUrlComponentChanged:!0,bedrockResourceConsumptionSnapshot:!0,deviceStartupMetrics:!0,mdxSignIn:!0,tvhtml5KeyboardLogging:!0,tvhtml5StartupSoundEvent:!0,tvhtml5LiveChatStatus:!0,tvhtml5DeviceStorageStatus:!0,tvhtml5LocalStorage:!0,directSignInEvent:!0,finalPayload:!0,tvhtml5SearchCompleted:!0,tvhtml5KeyboardPerformance:!0,adNotifyFailure:!0,latencyActionSpan:!0,tvhtml5AccountDialogOpened:!0,
tvhtml5ApiTest:!0};var yg=0,zg=sc?"webkit":rc?"moz":pc?"ms":oc?"o":"";A("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++yg},void 0);var Ag={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Bg(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Ag||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Cg(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Bg.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Bg.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Bg.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ib=z.ytEventsEventsListeners||{};A("ytEventsEventsListeners",ib,void 0);var Dg=z.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Dg,void 0);
function Eg(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return hb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=La(e[4])&&La(d)&&mb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Fg=Ya(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Gg(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Eg(a,b,c,d);if(e)return e;e=++Dg.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Bg(h);if(!yd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Bg(h);
h.currentTarget=a;return c.call(a,h)};
g=pg(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Fg()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ib[e]=[a,b,c,g,d];return e}
function Hg(a){a&&("string"==typeof a&&(a=[a]),E(a,function(b){if(b in ib){var c=ib[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Fg()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ib[b]}}))}
;var Ig=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Jg(a,b){"function"===typeof a&&(a=pg(a));return window.setTimeout(a,b)}
function Kg(a){window.clearTimeout(a)}
;function Lg(a){this.C=a;this.i=null;this.m=0;this.B=null;this.A=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.L=Gg(window,"mousemove",Sa(this.T,this));a=Sa(this.J,this);"function"===typeof a&&(a=pg(a));this.U=window.setInterval(a,25)}
D(Lg,J);Lg.prototype.T=function(a){void 0===a.h&&Cg(a);var b=a.h;void 0===a.i&&Cg(a);this.i=new qd(b,a.i)};
Lg.prototype.J=function(){if(this.i){var a=Ig();if(0!=this.m){var b=this.B,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.A)/this.A)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.C();this.A=d}this.m=a;this.B=this.i;this.l=(this.l+1)%4}};
Lg.prototype.D=function(){window.clearInterval(this.U);Hg(this.L)};function Mg(){}
function Ng(a,b){return Og(a,0,b)}
function Pg(a,b){return Og(a,1,b)}
;function Qg(){Mg.apply(this,arguments)}
v(Qg,Mg);function Rg(){Qg.h||(Qg.h=new Qg);return Qg.h}
function Og(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Jg(a,c||0)}
function Sg(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):Kg(a)}}
Qg.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
Qg.prototype.pause=function(){var a=C("yt.scheduler.instance.pause");a&&a()};Rg();var Tg={};
function Ug(a){var b=void 0===a?{}:a;a=void 0===b.Lb?!1:b.Lb;b=void 0===b.vb?!0:b.vb;if(null==C("_lact",window)){var c=parseInt(F("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Vg();Gg(document,"keydown",Vg);Gg(document,"keyup",Vg);Gg(document,"mousedown",Vg);Gg(document,"mouseup",Vg);a?Gg(window,"touchmove",function(){Wg("touchmove",200)},{passive:!0}):(Gg(window,"resize",function(){Wg("resize",200)}),b&&Gg(window,"scroll",function(){Wg("scroll",200)}));
new Lg(function(){Wg("mouse",100)});
Gg(document,"touchstart",Vg,{passive:!0});Gg(document,"touchend",Vg,{passive:!0})}}
function Wg(a,b){Tg[a]||(Tg[a]=!0,Pg(function(){Vg();Tg[a]=!1},b))}
function Vg(){null==C("_lact",window)&&Ug();var a=Date.now();A("_lact",a,window);-1==C("_fact",window)&&A("_fact",a,window);(a=C("ytglobal.ytUtilActivityCallback_"))&&a()}
function Xg(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function Yg(){var a=Zg;C("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a,void 0)}
function $g(a){A("yt.ads.biscotti.lastId_",a,void 0)}
;var ah=/^[\w.]*$/,bh={q:!0,search_query:!0};function ch(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=dh(f[0]||""),h=dh(f[1]||"");g in c?Array.isArray(c[g])?fb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(ch);k.args=[{key:l,value:f[1],query:a,method:eh==n?"unchanged":n}];bh.hasOwnProperty(l)||rg(k)}}return c}
var eh=String(ch);function fh(a){var b=[];gb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];E(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function gh(a){"?"==a.charAt(0)&&(a=a.substr(1));return ch(a,"&")}
function hh(){var a=window.location.href;return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),gh(1<a.length?a[1]:a[0])):{}}
function ih(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=gh(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return kc(a,e)+d}
function jh(a){if(!b)var b=window.location.href;var c=a.match(fc)[1]||null,d=hc(a);c&&d?(a=a.match(fc),b=b.match(fc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?hc(b)==d&&(Number(b.match(fc)[4]||null)||null)==(Number(a.match(fc)[4]||null)||null):!0;return a}
function dh(a){return a&&a.match(ah)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function kh(a){var b=lh;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Gd;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Na){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?gd:g;try{var h=g.history.length}catch(Na){h=0}e.u_his=h;var k;e.u_h=null==(k=gd.screen)?void 0:k.height;var l;e.u_w=null==(l=gd.screen)?void 0:l.width;var n;e.u_ah=null==(n=gd.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=gd.screen)?void 0:p.availWidth;var r;e.u_cd=null==(r=gd.screen)?void 0:r.colorDepth}catch(Na){}h=b.h;try{var q=h.screenX;var y=h.screenY}catch(Na){}try{var B=h.outerWidth;var G=h.outerHeight}catch(Na){}try{var R=h.innerWidth;var P=h.innerHeight}catch(Na){}try{var K=h.screenLeft;var ea=h.screenTop}catch(Na){}try{R=h.innerWidth,P=h.innerHeight}catch(Na){}try{var Ef=h.screen.availWidth;var fn=h.screen.availTop}catch(Na){}q=[K,ea,q,y,Ef,fn,B,G,R,P];y=b.h.top;try{var Mb=(y||window).document,Aa=
"CSS1Compat"==Mb.compatMode?Mb.documentElement:Mb.body;var Da=(new rd(Aa.clientWidth,Aa.clientHeight)).round()}catch(Na){Da=new rd(-12245933,-12245933)}Mb=Da;Da={};Aa=new Td;z.SVGElement&&z.document.createElementNS&&Aa.set(0);y=Dd();y["allow-top-navigation-by-user-activation"]&&Aa.set(1);y["allow-popups-to-escape-sandbox"]&&Aa.set(2);z.crypto&&z.crypto.subtle&&Aa.set(3);z.TextDecoder&&z.TextEncoder&&Aa.set(4);Aa=Ud(Aa);Da.bc=Aa;Da.bih=Mb.height;Da.biw=Mb.width;Da.brdim=q.join();b=b.i;b=(Da.vis={visible:1,
hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Da.wgl=!!gd.WebGLRenderingContext,Da);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var lh=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return fh(kh(a))},void 0);Date.now();var mh="XMLHttpRequest"in z?function(){return new XMLHttpRequest}:null;
function nh(){if(!mh)return null;var a=mh();return"open"in a?a:null}
function oh(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var ph={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},qh="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ha("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),rh=!1;
function sh(a,b){b=void 0===b?{}:b;var c=jh(a),d=N("web_ajax_ignore_global_headers_if_set"),e;for(e in ph){var f=F(ph[e]);!f||!c&&hc(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!hc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!hc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!hc(a))b["X-YouTube-Ad-Signals"]=fh(kh(void 0));return b}
function th(a){var b=window.location.search,c=hc(a);N("debug_handle_relative_url_for_query_forward_killswitch")||c||!jh(a)||(c=document.location.hostname);var d=gc(a.match(fc)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=gh(b),f={};E(qh,function(g){e[g]&&(f[g]=e[g])});
return ih(a,f||{},!1)}
function uh(a,b){var c=b.format||"JSON";a=vh(a,b);var d=wh(a,b),e=!1,f=xh(a,function(k){if(!e){e=!0;h&&Kg(h);var l=oh(k),n=null,p=400<=k.status&&500>k.status,r=500<=k.status&&600>k.status;if(l||p||r)n=yh(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||z;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,k,n)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=Jg(function(){e||(e=!0,f.abort(),Kg(h),g.call(b.context||z,f))},b.timeout)}return f}
function vh(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=F("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=ih(a,b||{},!0);return a}
function wh(a,b){var c=F("XSRF_FIELD_NAME",void 0),d=F("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=F("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||hc(a)&&!b.withCredentials&&hc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=gh(e),qb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):jc(e));f=e||f&&!jb(f);!rh&&f&&
"POST"!=b.method&&(rh=!0,qg(Error("AJAX request with postData should use POST")));return e}
function yh(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,rg(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?zh(a):null)e={},E(a.getElementsByTagName("*"),function(g){e[g.tagName]=Ah(g)})}d&&Bh(e);
return e}
function Bh(a){if(La(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;vb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Zb(a[b],null);a[c]=d}else Bh(a[b])}}
function zh(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Ah(a){var b="";E(a.childNodes,function(c){b+=c.nodeValue});
return b}
function xh(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&pg(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=nh();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;N("debug_forward_web_query_parameters")&&(a=th(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=sh(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Ch=Dc||Ec;function Dh(a){var b=Sb;return b?0<=b.toLowerCase().indexOf(a):!1}
;var Eh={},Fh=0;
function Gh(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Dh("cobalt")){if(a){a instanceof Kb||(a="object"==typeof a&&a.X?a.W():String(a),Qb.test(a)?a=new Kb(a,Lb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Pb))&&Ob.test(b[1])?new Kb(a,Lb):null));b=Nb(a||Rb);if("about:invalid#zClosurez"===b||b.startsWith("data"))a="";else{if(b instanceof Yb)a=b;else{var f="object"==typeof b;a=null;f&&b.Ja&&(a=b.Fa());b=f&&b.X?b.W():String(b);Jb.test(b)&&(-1!=b.indexOf("&")&&(b=b.replace(Db,"&amp;")),-1!=b.indexOf("<")&&
(b=b.replace(Eb,"&lt;")),-1!=b.indexOf(">")&&(b=b.replace(Fb,"&gt;")),-1!=b.indexOf('"')&&(b=b.replace(Gb,"&quot;")),-1!=b.indexOf("'")&&(b=b.replace(Hb,"&#39;")),-1!=b.indexOf("\x00")&&(b=b.replace(Ib,"&#0;")));a=Zb(b,a)}a instanceof Yb&&a.constructor===Yb?a=a.h:(Ja(a),a="type_error:SafeHtml");a=encodeURIComponent(String(pf(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=vd("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))}}else if(e)xh(a,
b,"POST",e,d);else if(F("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)xh(a,b,"GET","",d);else{b:{try{var g=new Xa({url:a});if(g.j&&g.i||g.l){var h=gc(a.match(fc)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(lc);d:{for(c=0;0<=(c=a.indexOf("ri",c))&&c<l;){var n=a.charCodeAt(c-1);if(38==n||63==n){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var r=c;break d}}c+=3}r=-1}if(0>r)var q=null;else{var y=a.indexOf("&",r);if(0>y||y>l)y=l;r+=3;q=decodeURIComponent(a.substr(r,y-r).replace(/\+/g,
" "))}k="1"!==q}f=!k;break b}}catch(B){}f=!1}f?Hh(a)?(b&&b(),f=!0):f=!1:f=!1;f||Ih(a,b)}}
function Jh(a,b,c){c=void 0===c?"":c;Hh(a,c)?b&&b():Gh(a,b,void 0,void 0,c)}
function Hh(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Ih(a,b){var c=new Image,d=""+Fh++;Eh[d]=c;c.onload=c.onerror=function(){b&&Eh[d]&&b();delete Eh[d]};
c.src=a}
;var Kh=z.ytPubsubPubsubInstance||new L,Lh=z.ytPubsubPubsubSubscribedKeys||{},Mh=z.ytPubsubPubsubTopicToKeys||{},Nh=z.ytPubsubPubsubIsSynchronous||{};function Oh(a,b){var c=Ph();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Lh[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Nh[a]?f():Jg(f,0)}catch(g){qg(g)}},void 0);
Lh[d]=!0;Mh[a]||(Mh[a]=[]);Mh[a].push(d);return d}return 0}
function Qh(a){var b=Ph();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),E(a,function(c){b.unsubscribeByKey(c);delete Lh[c]}))}
function Rh(a,b){var c=Ph();c&&c.publish.apply(c,arguments)}
function Sh(a){var b=Ph();if(b)if(b.clear(a),a)Th(a);else for(var c in Mh)Th(c)}
function Ph(){return z.ytPubsubPubsubInstance}
function Th(a){Mh[a]&&(a=Mh[a],E(a,function(b){Lh[b]&&delete Lh[b]}),a.length=0)}
L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.ka;L.prototype.publish=L.prototype.da;L.prototype.clear=L.prototype.clear;A("ytPubsubPubsubInstance",Kh,void 0);A("ytPubsubPubsubTopicToKeys",Mh,void 0);A("ytPubsubPubsubIsSynchronous",Nh,void 0);A("ytPubsubPubsubSubscribedKeys",Lh,void 0);var Uh=window,O=Uh.ytcsi&&Uh.ytcsi.now?Uh.ytcsi.now:Uh.performance&&Uh.performance.timing&&Uh.performance.now&&Uh.performance.timing.navigationStart?function(){return Uh.performance.timing.navigationStart+Uh.performance.now()}:function(){return(new Date).getTime()};var Vh=vg("initial_gel_batch_timeout",2E3),Wh=Math.pow(2,16)-1,Xh=void 0,Yh=0,Zh=0,$h=0,ai=!0,bi=z.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",bi,void 0);var ci=z.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",ci,void 0);
function di(a,b){if("log_event"===a.endpoint){var c="";a.ta?c="visitorOnlyApprovedKey":a.cttAuthInfo&&(ci[a.cttAuthInfo.token]=ei(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=bi.get(c)||[];bi.set(c,d);d.push(a.payload);b&&(Xh=new b);a=vg("tvhtml5_logging_max_batch")||vg("web_logging_max_batch")||100;b=O();d.length>=a?fi({writeThenSend:!0},N("flush_only_full_queue")?c:void 0):10<=b-$h&&(gi(),$h=b)}}
function hi(a,b){if("log_event"===a.endpoint){var c="";a.ta?c="visitorOnlyApprovedKey":a.cttAuthInfo&&(ci[a.cttAuthInfo.token]=ei(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=new Map;d.set(c,[a.payload]);b&&(Xh=new b);return new wf(function(e){Xh&&Xh.isReady()?ii(d,e,{bypassNetworkless:!0},!0):e()})}}
function fi(a,b){a=void 0===a?{}:a;new wf(function(c){Kg(Yh);Kg(Zh);Zh=0;if(Xh&&Xh.isReady())if(void 0!==b){var d=new Map,e=bi.get(b)||[];d.set(b,e);ii(d,c,a);bi.delete(b)}else ii(bi,c,a),bi.clear();else gi(),c()})}
function gi(){N("web_gel_timeout_cap")&&!Zh&&(Zh=Jg(function(){fi({writeThenSend:!0})},6E4));
Kg(Yh);var a=F("LOGGING_BATCH_TIMEOUT",vg("web_gel_debounce_ms",1E4));N("shorten_initial_gel_batch_timeout")&&ai&&(a=Vh);Yh=Jg(function(){fi({writeThenSend:!0})},a)}
function ii(a,b,c,d){var e=Xh;c=void 0===c?{}:c;var f=Math.round(O()),g=a.size;a=u(a);for(var h=a.next();!h.done;h=a.next()){var k=u(h.value);h=k.next().value;var l=k=k.next().value;k=ob({context:ji(e.config_||ki())});k.events=l;(l=ci[h])&&li(k,h,l);delete ci[h];h="visitorOnlyApprovedKey"===h;mi(k,f,h);N("always_send_and_write")&&(c.writeThenSend=!1);N("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Jh("/generate_204");ni(e,"log_event",k,{retry:!0,onSuccess:function(){g--;
g||b()},
onError:function(){g--;g||b()},
gb:c,ta:h,Hm:!!d});ai=!1}}
function mi(a,b,c){a.requestTimeMs=String(b);N("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=F("EVENT_ID",void 0))&&((c=F("BATCH_CLIENT_COUNTER",void 0)||0)||(c=Math.floor(Math.random()*Wh/2)),c++,c>Wh&&(c=1),M("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function li(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function ei(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var oi=z.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",oi,void 0);
function pi(a,b,c,d){d=void 0===d?{}:d;if(N("lr_drop_other_and_business_payloads")){if(xg[a]||wg[a])return}else if(N("lr_drop_other_payloads")&&xg[a])return;var e={},f=Math.round(d.timestamp||O());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=Xg();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};N("log_sequence_info_on_gel_web")&&d.ba&&(a=e.context,b=d.ba,oi[b]=b in oi?oi[b]+1:0,a.sequence={index:oi[b],groupKey:b},d.wb&&delete oi[d.ba]);(d.Qm?hi:di)({endpoint:"log_event",payload:e,
cttAuthInfo:d.cttAuthInfo,ta:d.ta},c)}
;function qi(){if(!z.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return z.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":z.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":z.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":z.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function ri(a,b,c,d,e){Od.set(""+a,b,{La:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
;var si=C("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",si,void 0);function ti(){this.h=F("ALT_PREF_COOKIE_NAME","PREF");this.i=F("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Od.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(si[d]=c.toString())}}}
ti.prototype.get=function(a,b){ui(a);vi(a);a=void 0!==si[a]?si[a].toString():null;return null!=a?a:b?b:""};
ti.prototype.set=function(a,b){ui(a);vi(a);if(null==b)throw Error("ExpectedNotNull");si[a]=b.toString()};
ti.prototype.remove=function(a){ui(a);vi(a);delete si[a]};
ti.prototype.clear=function(){for(var a in si)delete si[a]};
function vi(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function ui(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function wi(a){a=void 0!==si[a]?si[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ia(ti);var xi={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},yi={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function zi(){var a=z.navigator;return a?a.connection:void 0}
;function Ai(){return"INNERTUBE_API_KEY"in lg&&"INNERTUBE_API_VERSION"in lg}
function ki(){return{innertubeApiKey:F("INNERTUBE_API_KEY",void 0),innertubeApiVersion:F("INNERTUBE_API_VERSION",void 0),yb:F("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),zb:F("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Bb:F("INNERTUBE_CONTEXT_HL",void 0),Ab:F("INNERTUBE_CONTEXT_GL",void 0),Cb:F("INNERTUBE_HOST_OVERRIDE",void 0)||"",Eb:!!F("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Db:!!F("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:F("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function ji(a){var b={client:{hl:a.Bb,gl:a.Ab,clientName:a.zb,clientVersion:a.innertubeContextClientVersion,configInfo:a.yb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=z.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=F("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=F("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=F("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===
d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});f=b.client.clientName;if("WEB"===f||"MWEB"===f||1===f||2===f){if(!N("web_include_display_mode_killswitch")){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=qi()}}else if(g=b.client.clientName,("WEB_REMIX"===g||76===g)&&!N("music_web_display_mode_killswitch")){var h;b.client.fb=null!=(h=b.client.fb)?h:{};b.client.fb.webDisplayMode=qi()}a.appInstallData&&
(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);F("DELEGATED_SESSION_ID")&&!N("pageid_as_header_web")&&(b.user={onBehalfOfUser:F("DELEGATED_SESSION_ID")});a:{if(h=zi()){a=xi[h.type||"unknown"]||"CONN_UNKNOWN";h=xi[h.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==h&&(a=h);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==h){a=h;break a}}a=void 0}a&&(b.client.connectionType=a);N("web_log_effective_connection_type")&&
(a=zi(),a=null!==a&&void 0!==a&&a.effectiveType?yi.hasOwnProperty(a.effectiveType)?yi[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&(b.client.effectiveConnectionType=a));a=Object;h=a.assign;g=b.client;f={};e=u(Object.entries(gh(F("DEVICE",""))));for(c=e.next();!c.done;c=e.next())d=u(c.value),c=d.next().value,d=d.next().value,"cbrand"===c?f.deviceMake=d:"cmodel"===c?f.deviceModel=d:"cbr"===c?f.browserName=d:"cbrver"===c?f.browserVersion=d:"cos"===c?f.osName=d:"cosver"===c?f.osVersion=
d:"cplatform"===c&&(f.platform=d);b.client=h.call(a,g,f);return b}
function Bi(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||F("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Fm||F("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().Em:b=Sd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=F("SESSION_INDEX",0),N("pageid_as_header_web")&&(d["X-Goog-PageId"]=F("DELEGATED_SESSION_ID")));return d}
;function Ci(a){a=Object.assign({},a);delete a.Authorization;var b=Sd();if(b){var c=new le;c.update(F("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=Ic(c.digest(),3)}return a}
;function Di(a){var b=new Zf;(b=b.isAvailable()?a?new eg(b,a):b:null)||(a=new $f(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Vf(a):null;this.i=document.domain||window.location.hostname}
Di.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(pf(b))}catch(f){return}else e=escape(b);ri(a,e,c,this.i)};
Di.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Od.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Di.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Od.remove(""+a,"/",void 0===b?"youtube.com":b)};var Ei;function Fi(){Ei||(Ei=new Di("yt.innertube"));return Ei}
function Gi(a,b,c,d){if(d)return null;d=Fi().get("nextId",!0)||1;var e=Fi().get("requests",!0)||{};e[d]={method:a,request:b,authState:Ci(c),requestTime:Math.round(O())};Fi().set("nextId",d+1,86400,!0);Fi().set("requests",e,86400,!0);return d}
function Hi(a){var b=Fi().get("requests",!0)||{};delete b[a];Fi().set("requests",b,86400,!0)}
function Ii(a){var b=Fi().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(O())-d.requestTime)){var e=d.authState,f=Ci(Bi(!1));mb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(O())),ni(a,d.method,e,{}));delete b[c]}}Fi().set("requests",b,86400,!0)}}
;var Ji=function(){var a;return function(){a||(a=new Di("ytidb"));return a}}();
function Ki(){var a;return null===(a=Ji())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Li=[],Mi=!1;function Ni(a){Mi||(Li.push({type:"ERROR",payload:a}),10<Li.length&&Li.shift())}
function Oi(a,b){Mi||(Li.push({type:"EVENT",eventType:a,payload:b}),10<Li.length&&Li.shift())}
;function Pi(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(ha(c))}
v(Pi,Error);function Qi(){try{return Ri(),!0}catch(a){return!1}}
function Ri(){if(void 0!==F("DATASYNC_ID",void 0))return F("DATASYNC_ID",void 0);throw new Pi("Datasync ID not set","unknown");}
;function Si(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Ti(a){return a.substr(0,a.indexOf(":"))||a}
;var Ui={},Vi=(Ui.AUTH_INVALID="No user identifier specified.",Ui.EXPLICIT_ABORT="Transaction was explicitly aborted.",Ui.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Ui.MISSING_INDEX="Index not created.",Ui.MISSING_OBJECT_STORE="Object store not created.",Ui.DB_DELETED_BY_MISSING_OBJECT_STORE="Database is deleted because an expected object store was not created.",Ui.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",Ui.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",
Ui.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Ui.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Ui.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Ui),Wi={},Xi=(Wi.AUTH_INVALID="ERROR",Wi.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Wi.EXPLICIT_ABORT="IGNORED",Wi.IDB_NOT_SUPPORTED="ERROR",Wi.MISSING_INDEX="WARNING",Wi.MISSING_OBJECT_STORE="ERROR",Wi.DB_DELETED_BY_MISSING_OBJECT_STORE=
"WARNING",Wi.QUOTA_EXCEEDED="WARNING",Wi.QUOTA_MAYBE_EXCEEDED="WARNING",Wi.UNKNOWN_ABORT="WARNING",Wi.INCOMPATIBLE_DB_VERSION="WARNING",Wi),Yi={},Zi=(Yi.AUTH_INVALID=!1,Yi.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Yi.EXPLICIT_ABORT=!1,Yi.IDB_NOT_SUPPORTED=!1,Yi.MISSING_INDEX=!1,Yi.MISSING_OBJECT_STORE=!1,Yi.DB_DELETED_BY_MISSING_OBJECT_STORE=!1,Yi.QUOTA_EXCEEDED=!1,Yi.QUOTA_MAYBE_EXCEEDED=!0,Yi.UNKNOWN_ABORT=!0,Yi.INCOMPATIBLE_DB_VERSION=!1,Yi);
function Q(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Vi[a]:c;d=void 0===d?Xi[a]:d;e=void 0===e?Zi[a]:e;Pi.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Q.prototype)}
v(Q,Pi);function $i(a){Q.call(this,"MISSING_OBJECT_STORE",{Hb:a},Vi.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,$i.prototype)}
v($i,Q);function aj(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,aj.prototype)}
v(aj,Error);var bj=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function cj(a,b,c,d){b=Ti(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Q)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Q("QUOTA_EXCEEDED",a);if(Fc&&"UnknownError"===e.name)return new Q("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof aj)return new Q("MISSING_INDEX",Object.assign(Object.assign({},a),{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&bj.some(function(f){return e.message.includes(f)}))return new Q("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Q("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign(Object.assign({},a),{name:"IdbError",Mm:e.name})];e.level="WARNING";return e}
function dj(a,b,c){var d=Ki();return new Q("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null===d||void 0===d?void 0:d.hasSucceededOnce}})}
;function ej(a){if(!a)throw Error();throw a;}
function fj(a){return a}
function gj(a){this.h=a}
function S(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
S.all=function(a){return new S(new gj(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={fa:0};f.fa<a.length;f={fa:f.fa},++f.fa)hj(S.resolve(a[f.fa]).then(function(g){return function(h){d[g.fa]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
S.resolve=function(a){return new S(new gj(function(b,c){a instanceof S?a.then(b,c):b(a)}))};
S.reject=function(a){return new S(new gj(function(b,c){c(a)}))};
S.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:fj,e=null!==b&&void 0!==b?b:ej;return new S(new gj(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){ij(c,c,d,f,g)}),c.onRejected.push(function(){jj(c,c,e,f,g)})):"FULFILLED"===c.state.status?ij(c,c,d,f,g):"REJECTED"===c.state.status&&jj(c,c,e,f,g)}))};
function hj(a,b){a.then(void 0,b)}
function ij(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof S?kj(a,b,f,d,e):d(f)}catch(g){e(g)}}
function jj(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof S?kj(a,b,f,d,e):d(f)}catch(g){e(g)}}
function kj(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof S?kj(a,b,f,d,e):d(f)},function(f){e(f)})}
;function lj(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function mj(a){return new Promise(function(b,c){lj(a,b,c)})}
function T(a){return new S(new gj(function(b,c){lj(a,b,c)}))}
;function nj(a,b){return new S(new gj(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function oj(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(O());this.i=!1}
m=oj.prototype;m.add=function(a,b,c){return pj(this,[a],{mode:"readwrite",K:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return pj(this,[a],{mode:"readwrite",K:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return pj(this,[a],{mode:"readonly",K:!0},function(c){return c.objectStore(a).count(b)})};
function qj(a,b,c){a=a.h.createObjectStore(b,c);return new rj(a)}
m.delete=function(a,b){return pj(this,[a],{mode:"readwrite",K:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return pj(this,[a],{mode:"readonly",K:!0},function(c){return c.objectStore(a).get(b)})};
function sj(a,b){return pj(a,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(c){c=c.objectStore("LogsRequestsStore");return T(c.h.put(b,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function pj(a,b,c,d){return I(a,function f(){var g=this,h,k,l,n,p,r,q,y,B,G,R,P;return x(f,function(K){switch(K.h){case 1:var ea={mode:"readonly",K:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?ea.mode=c:Object.assign(ea,c);h=ea;g.transactionCount++;k=h.K?3:1;l=0;case 2:if(n){K.u(3);break}l++;p=Math.round(O());sa(K,4);r=g.h.transaction(b,h.mode);ea=new tj(r);ea=uj(ea,d);return w(K,ea,6);case 6:return q=K.i,y=Math.round(O()),vj(g,p,y,l,void 0,b.join(),h),K.return(q);case 4:B=ta(K);G=Math.round(O());
R=cj(B,g.h.name,b.join(),g.h.version);if((P=R instanceof Q&&!R.h)||l>=k)vj(g,p,G,l,R,b.join(),h),n=R;K.u(2);break;case 3:return K.return(Promise.reject(n))}})})}
function vj(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Q&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Oi("QUOTA_EXCEEDED",{dbName:Ti(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Q&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),Oi("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),wj(a,!1,d,f,b,g.tag),Ni(e)):wj(a,!0,d,f,b,g.tag)}
function wj(a,b,c,d,e,f){Oi("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function rj(a){this.h=a}
m=rj.prototype;m.add=function(a,b){return T(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return T(this.h.clear()).then(function(){})};
m.count=function(a){return T(this.h.count(a))};
function xj(a,b){return yj(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?xj(this,a):T(this.h.delete(a))};
m.get=function(a){return T(this.h.get(a))};
m.index=function(a){try{return new zj(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new aj(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function yj(a,b,c){a=a.h.openCursor(b.query,b.direction);return Aj(a).then(function(d){return nj(d,c)})}
function tj(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=Q;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function uj(a,b){var c=new Promise(function(d,e){try{hj(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
tj.prototype.abort=function(){this.h.abort();this.i=!0;throw new Q("EXPLICIT_ABORT");};
tj.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new rj(a),this.j.set(a,b));return b};
function zj(a){this.h=a}
m=zj.prototype;m.count=function(a){return T(this.h.count(a))};
m.delete=function(a){return Bj(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return T(this.h.get(a))};
m.getKey=function(a){return T(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function Bj(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Aj(a).then(function(d){return nj(d,c)})}
function Cj(a,b){this.request=a;this.cursor=b}
function Aj(a){return T(a).then(function(b){return b?new Cj(a,b):null})}
m=Cj.prototype;m.advance=function(a){this.cursor.advance(a);return Aj(this.request)};
m.continue=function(a){this.cursor.continue(a);return Aj(this.request)};
m.delete=function(){return T(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return T(this.cursor.update(a))};function Dj(a,b,c){return new Promise(function(d,e){function f(){r||(r=new oj(g.result,{closed:p}));return r}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.Wb,n=c.upgrade,p=c.closed,r;g.addEventListener("upgradeneeded",function(q){try{if(null===q.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");q.dataLoss&&"none"!==q.dataLoss&&Oi("IDB_DATA_CORRUPTED",{reason:q.dataLossMessage||"unknown reason",dbName:Ti(a)});var y=f(),B=new tj(g.transaction);
n&&n(y,function(G){return q.oldVersion<G&&q.newVersion>=G},B);
B.done.catch(function(G){e(G)})}catch(G){e(G)}});
g.addEventListener("success",function(){var q=g.result;k&&q.addEventListener("versionchange",function(){k(f())});
q.addEventListener("close",function(){Oi("IDB_UNEXPECTEDLY_CLOSED",{dbName:Ti(a),dbVersion:q.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Ej(a,b,c){c=void 0===c?{}:c;return Dj(a,b,c)}
function Fj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f,g;return x(d,function(h){e=self.indexedDB.deleteDatabase(a);f=b;(g=f.blocked)&&e.addEventListener("blocked",function(){g()});
return w(h,mj(e),0)})})}
;function Gj(a,b){this.name=a;this.options=b;this.l=!0;this.j=!1}
Gj.prototype.i=function(a,b,c){c=void 0===c?{}:c;return Ej(a,b,c)};
Gj.prototype.delete=function(a){a=void 0===a?{}:a;return Fj(this.name,a)};
function Hj(a,b){return new Q("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Ij(a,b){if(!b)throw dj("openWithToken",Ti(a.name));return a.open()}
Gj.prototype.open=function(){function a(){return I(c,function g(){var h,k,l,n=this,p,r,q,y,B;return x(g,function(G){switch(G.h){case 1:return l=null!==(h=Error().stack)&&void 0!==h?h:"",sa(G,2),w(G,n.i(n.name,n.options.version,e),4);case 4:p=G.i;a:{var R=n.options;for(var P=u(Object.keys(R.xa)),K=P.next();!K.done;K=P.next()){K=K.value;var ea=R.xa[K],Ef=void 0===ea.Nb?Number.MAX_VALUE:ea.Nb;if(p.h.version>=ea.Ea&&!(p.h.version>=Ef)&&!p.h.objectStoreNames.contains(K)){R=K;break a}}R=void 0}r=R;if(void 0===
r){G.u(5);break}if(n.j){G.u(6);break}n.j=!0;return w(G,n.delete(),7);case 7:return Ni(new Q("DB_DELETED_BY_MISSING_OBJECT_STORE",{dbName:n.name,Hb:r})),G.return(a());case 6:throw new $i(r);case 5:return G.return(p);case 2:q=ta(G);if(q instanceof DOMException?"VersionError"!==q.name:"DOMError"in self&&q instanceof DOMError?"VersionError"!==q.name:!(q instanceof Object&&"message"in q)||"An attempt was made to open a database using a lower version than the existing version."!==q.message){G.u(8);break}return w(G,
n.i(n.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),9);case 9:y=G.i;B=y.h.version;if(void 0!==n.options.version&&B>n.options.version+1)throw y.close(),n.l=!1,Hj(n,B);return G.return(y);case 8:throw b(),q instanceof Error&&!N("ytidb_async_stack_killswitch")&&(q.stack=q.stack+"\n"+l.substring(l.indexOf("\n")+1)),cj(q,n.name,"",null!==(k=n.options.version)&&void 0!==k?k:-1);}})})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw Hj(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Wb:b,upgrade:this.options.upgrade};return this.h=d=a()};var Jj=new Gj("YtIdbMeta",{xa:{databases:{Ea:1}},upgrade:function(a,b){b(1)&&qj(a,"databases",{keyPath:"actualName"})}});
function Kj(a,b){return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Ij(Jj,b),2);e=f.i;return f.return(pj(e,["databases"],{K:!0,mode:"readwrite"},function(g){var h=g.objectStore("databases");return h.get(a.actualName).then(function(k){if(k?a.actualName!==k.actualName||a.publicName!==k.publicName||a.userIdentifier!==k.userIdentifier:1)return T(h.h.put(a,void 0)).then(function(){})})}))})})}
function Lj(a,b){return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return a?w(f,Ij(Jj,b),2):f.return();e=f.i;return f.return(e.delete("databases",a))})})}
function Mj(a,b){return I(this,function d(){var e,f;return x(d,function(g){return 1==g.h?(e=[],w(g,Ij(Jj,b),2)):3!=g.h?(f=g.i,w(g,pj(f,["databases"],{K:!0,mode:"readonly"},function(h){e.length=0;return yj(h.objectStore("databases"),{},function(k){a(k.getValue())&&e.push(k.getValue());return k.continue()})}),3)):g.return(e)})})}
function Nj(a){return Mj(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
;var Oj,Pj=new function(){}(new function(){});
function Qj(){return I(this,function b(){var c,d,e;return x(b,function(f){switch(f.h){case 1:c=Ki();if(null===c||void 0===c?0:c.hasSucceededOnce)return f.return(!0);var g;if(g=Ch)g=/WebKit\/([0-9]+)/.exec(Sb),g=!!(g&&600<=parseInt(g[1],10));g&&(g=/WebKit\/([0-9]+)/.exec(Sb),g=!(g&&602<=parseInt(g[1],10)));if(g||qc)return f.return(!1);try{if(d=self,!(d.indexedDB&&d.IDBIndex&&d.IDBKeyRange&&d.IDBObjectStore))return f.return(!1)}catch(h){return f.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in
IDBTransaction.prototype))return f.return(!1);sa(f,2);e={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(f,Kj(e,Pj),4);case 4:return w(f,Lj("yt-idb-test-do-not-use",Pj),5);case 5:return f.return(!0);case 2:return ta(f),f.return(!1)}})})}
function Rj(){if(void 0!==Oj)return Oj;Mi=!0;return Oj=Qj().then(function(a){Mi=!1;var b,c;null!==(b=Ji())&&void 0!==b&&b.h&&(b=Ki(),b={hasSucceededOnce:(null===b||void 0===b?void 0:b.hasSucceededOnce)||a},null===(c=Ji())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0));return a})}
function Sj(){return Rj().then(function(a){return a?Pj:void 0})}
;new function(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})};function Tj(a){if(!Qi())throw a=new Q("AUTH_INVALID",{dbName:a}),Ni(a),a;var b=Ri();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Uj(a,b,c,d){var e;return I(this,function g(){var h,k,l,n,p;return x(g,function(r){switch(r.h){case 1:return h=null!==(e=Error().stack)&&void 0!==e?e:"",w(r,Sj(),2);case 2:k=r.i;if(!k)throw l=dj("openDbImpl",a,b),N("ytidb_async_stack_killswitch")||(l.stack=l.stack+"\n"+h.substring(h.indexOf("\n")+1)),Ni(l),l;Si(a);n=c?{actualName:a,publicName:a,userIdentifier:void 0}:Tj(a);sa(r,3);return w(r,Kj(n,k),5);case 5:return w(r,Ej(n.actualName,b,d),6);case 6:return r.return(r.i);case 3:return p=ta(r),
sa(r,7),w(r,Lj(n.actualName,k),9);case 9:r.h=8;r.m=0;break;case 7:ta(r);case 8:throw p;}})})}
function Vj(a,b,c){c=void 0===c?{}:c;return Uj(a,b,!1,c)}
function Wj(a,b,c){c=void 0===c?{}:c;return Uj(a,b,!0,c)}
function Xj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f;return x(d,function(g){if(1==g.h)return w(g,Sj(),2);if(3!=g.h){e=g.i;if(!e)return g.return();Si(a);f=Tj(a);return w(g,Fj(f.actualName,b),3)}return w(g,Lj(f.actualName,e),0)})})}
function Yj(a,b,c){var d=this;a=a.map(function(e){return I(d,function g(){return x(g,function(h){return 1==h.h?w(h,Fj(e.actualName,b),2):w(h,Lj(e.actualName,c),0)})})});
return Promise.all(a).then(function(){})}
function Zj(){var a=void 0===a?{}:a;return I(this,function c(){var d,e;return x(c,function(f){if(1==f.h)return w(f,Sj(),2);if(3!=f.h){d=f.i;if(!d)return f.return();Si("LogsDatabaseV2");return w(f,Nj(d),3)}e=f.i;return w(f,Yj(e,a,d),0)})})}
function ak(a,b){b=void 0===b?{}:b;return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Sj(),2);if(3!=f.h){e=f.i;if(!e)return f.return();Si(a);return w(f,Fj(a,b),3)}return w(f,Lj(a,e),0)})})}
;function bk(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ja=function(){};
this.now=Date.now;this.nb=null!==(b=a.nb)&&void 0!==b?b:100;this.lb=null!==(c=a.lb)&&void 0!==c?c:1;this.jb=null!==(d=a.jb)&&void 0!==d?d:2592E6;this.hb=null!==(e=a.hb)&&void 0!==e?e:12E4;this.kb=null!==(f=a.kb)&&void 0!==f?f:5E3;this.databaseToken=null!==(g=a.databaseToken)&&void 0!==g?g:void 0;this.va=!!a.va;this.sa=null!==(h=a.sa)&&void 0!==h?h:.1;this.za=null!==(k=a.za)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.ja&&(this.ja=a.ja);this.F=a.F;this.cb=a.cb;this.G=a.G;this.I=
a.I;this.S=a.S;this.Oa=a.Oa;this.Na=a.Na;this.databaseToken&&(!this.F||this.F("networkless_logging"))&&ck(this)}
function ck(a){I(a,function c(){var d=this;return x(c,function(e){if(!d.databaseToken)return e.return();dk(d);d.I.H()&&d.ma();d.I.Y(d.Oa,d.ma.bind(d));d.I.Y(d.Na,d.Ua.bind(d));d.h=!0;return d.va&&Math.random()<=d.sa?w(e,d.G.sb(d.databaseToken),0):e.u(0)})})}
m=bk.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.G.set(d,this.databaseToken).then(function(e){d.id=e;c.I.H()&&ek(c,d)}).catch(function(e){ek(c,d);
fk(c,e)})}else this.S(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.F&&this.F("nwl_skip_retry")&&(e.skipRetry=c);if(this.I.H()){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return I(d,function l(){var n=this,p;return x(l,function(r){if(1==r.h)return p=n,w(r,n.G.set(e,n.databaseToken).catch(function(q){fk(p,q)}),2);
f(g,h);r.h=0})})}}this.S(a,b,e.skipRetry)}else this.G.set(e,this.databaseToken).catch(function(g){d.S(a,b,e.skipRetry);
fk(d,g)})}else this.S(a,b,this.F&&this.F("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.G.ia(d.id,c.databaseToken):e=!0;c.I.aa&&c.F&&c.F("vss_network_hint")&&c.I.aa(!0);f(g,h)};
this.S(d.url,d.options);this.G.set(d,this.databaseToken).then(function(g){d.id=g;e&&c.G.ia(d.id,c.databaseToken)}).catch(function(g){fk(c,g)})}else this.S(a,b)};
m.ma=function(){var a=this;if(!this.databaseToken)throw dj("throttleSend");this.i||(this.i=Pg(function(){return I(a,function c(){var d=this,e;return x(c,function(f){if(1==f.h)return w(f,d.G.ab("NEW",d.databaseToken),2);if(3!=f.h)return e=f.i,e?w(f,ek(d,e),3):(d.Ua(),f.return());d.i&&(d.i=0,d.ma());f.h=0})})},this.nb))};
m.Ua=function(){Sg(this.i);this.i=0};
function ek(a,b){return I(a,function d(){var e=this,f,g;return x(d,function(h){switch(h.h){case 1:if(!e.databaseToken)throw f=dj("immediateSend"),f;if(void 0===b.id){h.u(2);break}return w(h,e.G.Gb(b.id,e.databaseToken),3);case 3:(g=h.i)?b=g:e.ja(Error("The request cannot be found in the database."));case 2:if(gk(e,b,e.jb)){h.u(4);break}e.ja(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){h.u(5);break}return w(h,e.G.ia(b.id,e.databaseToken),5);case 5:return h.return();
case 4:b.skipRetry||(b=hk(e,b));if(!b){h.u(0);break}if(!b.skipRetry||void 0===b.id){h.u(8);break}return w(h,e.G.ia(b.id,e.databaseToken),8);case 8:e.S(b.url,b.options,!!b.skipRetry),h.h=0}})})}
function hk(a,b){if(!a.databaseToken)throw dj("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){return I(a,function h(){var k=this,l,n;return x(h,function(p){switch(p.h){case 1:l=k;n=ik(f);if(!(k.F&&k.F("nwl_consider_error_code")&&n||k.F&&!k.F("nwl_consider_error_code")&&k.potentialEsfErrorCounter<=k.za)){p.u(2);break}if(!k.I.N){p.u(3);break}return w(p,k.I.N(),3);case 3:if(k.I.H()){p.u(2);break}c(e,f);if(!k.F||!k.F("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){p.u(6);break}return w(p,k.G.Pa(b.id,k.databaseToken,!1),6);case 6:return p.return();
case 2:if(k.F&&k.F("nwl_consider_error_code")&&!n&&k.potentialEsfErrorCounter>k.za)return p.return();k.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){p.u(8);break}return b.sendCount<k.lb?w(p,k.G.Pa(b.id,k.databaseToken),12):w(p,k.G.ia(b.id,k.databaseToken),8);case 12:Pg(function(){l.I.H()&&l.ma()},k.kb);
case 8:c(e,f),p.h=0}})})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return I(a,function h(){var k=this;return x(h,function(l){if(1==l.h)return void 0===(null===b||void 0===b?void 0:b.id)?l.u(2):w(l,k.G.ia(b.id,k.databaseToken),2);k.I.aa&&k.F&&k.F("vss_network_hint")&&k.I.aa(!0);d(e,f);l.h=0})})};
return b}
function gk(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function dk(a){if(!a.databaseToken)throw dj("retryQueuedRequests");a.G.ab("QUEUED",a.databaseToken).then(function(b){b&&!gk(a,b,a.hb)?Pg(function(){return I(a,function d(){var e=this;return x(d,function(f){if(1==f.h)return void 0===b.id?f.u(2):w(f,e.G.Pa(b.id,e.databaseToken),2);dk(e);f.h=0})})}):a.I.H()&&a.ma()})}
function fk(a,b){a.ob&&!a.I.H()?a.ob(b):a.handleError(b)}
function ik(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function jk(a,b){this.version=a;this.args=b}
;function kk(a,b){this.topic=a;this.h=b}
kk.prototype.toString=function(){return this.topic};var lk=C("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.ka;L.prototype.publish=L.prototype.da;L.prototype.clear=L.prototype.clear;A("ytPubsub2Pubsub2Instance",lk,void 0);var mk=C("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",mk,void 0);var nk=C("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",nk,void 0);var ok=C("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",ok,void 0);
A("ytPubsub2Pubsub2SkipSubKey",null,void 0);function pk(a,b){var c=qk();c&&c.publish.call(c,a.toString(),a,b)}
function rk(a){var b=sk,c=qk();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=C("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(mk[d])try{if(f&&b instanceof kk&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ca){var l=new h;h.ca=l.version}var n=h.ca}catch(p){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
eb(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){qg(p)}},ok[b.toString()]?C("yt.scheduler.instance")?Og(g,1,void 0):Jg(g,0):g())});
mk[d]=!0;nk[b.toString()]||(nk[b.toString()]=[]);nk[b.toString()].push(d);return d}
function tk(){var a=uk,b=rk(function(c){a.apply(void 0,arguments);vk(b)});
return b}
function vk(a){var b=qk();b&&("number"===typeof a&&(a=[a]),E(a,function(c){b.unsubscribeByKey(c);delete mk[c]}))}
function qk(){return C("ytPubsub2Pubsub2Instance")}
;function wk(a,b){Gj.call(this,a,b);this.options=b;Si(a)}
v(wk,Gj);function xk(a,b){var c;return function(){c||(c=new wk(a,b));return c}}
wk.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.Qa?Wj:Vj)(a,b,Object.assign({},c))};
wk.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Qa?ak:Xj)(this.name,a)};
function yk(a,b){return xk(a,b)}
;var zk;
function Ak(){if(zk)return zk();var a={};zk=yk("LogsDatabaseV2",{xa:(a.LogsRequestsStore={Ea:2},a),Qa:!1,upgrade:function(b,c,d){c(2)&&qj(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return zk()}
;function Bk(a){return Ij(Ak(),a)}
function Ck(a,b){return I(this,function d(){var e,f,g,h;return x(d,function(k){if(1==k.h)return e={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(k,Bk(b),2);if(3!=k.h)return f=k.i,g=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:F("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(k,sj(f,g),3);h=k.i;e.Xb=O();Dk(e);return k.return(h)})})}
function Ek(a,b){return I(this,function d(){var e,f,g,h,k,l,n;return x(d,function(p){if(1==p.h)return e={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(p,Bk(b),2);if(3!=p.h)return f=p.i,g=F("INNERTUBE_CONTEXT_CLIENT_NAME",0),h=[a,g,0],k=[a,g,O()],l=IDBKeyRange.bound(h,k),n=void 0,w(p,pj(f,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(r){return Bj(r.objectStore("LogsRequestsStore").index("newRequestV2"),{query:l,direction:"prev"},function(q){q.getValue()&&(n=q.getValue(),
"NEW"===a&&(n.status="QUEUED",q.update(n)))})}),3);
e.Xb=O();Dk(e);return p.return(n)})})}
function Fk(a,b){return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Bk(b),2);e=f.i;return f.return(pj(e,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){if(k)return k.status="QUEUED",T(h.h.put(k,void 0)).then(function(){return k})})}))})})}
function Gk(a,b,c){c=void 0===c?!0:c;return I(this,function e(){var f;return x(e,function(g){if(1==g.h)return w(g,Bk(b),2);f=g.i;return g.return(pj(f,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(h){var k=h.objectStore("LogsRequestsStore");return k.get(a).then(function(l){return l?(l.status="NEW",c&&(l.sendCount+=1),T(k.h.put(l,void 0)).then(function(){return l})):S.resolve(void 0)})}))})})}
function Hk(a,b){return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Bk(b),2);e=f.i;return f.return(e.delete("LogsRequestsStore",a))})})}
function Ik(a){return I(this,function c(){var d,e;return x(c,function(f){if(1==f.h)return w(f,Bk(a),2);d=f.i;e=O()-2592E6;return w(f,pj(d,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(g){return yj(g.objectStore("LogsRequestsStore"),{},function(h){if(h.getValue().timestamp<=e)return h.delete().then(function(){return h.continue()})})}),0)})})}
function Jk(){return I(this,function b(){return x(b,function(c){return w(c,Zj(),0)})})}
function Dk(a){N("nwl_csi_killswitch")||.01>=Math.random()&&pk("nwl_transaction_latency_payload",a)}
;var Kk={},Lk=yk("ServiceWorkerLogsDatabase",{xa:(Kk.SWHealthLog={Ea:1},Kk),Qa:!0,upgrade:function(a,b){b(1)&&qj(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Mk(a){return Ij(Lk(),a)}
function Nk(a){return I(this,function c(){var d,e;return x(c,function(f){if(1==f.h)return N("web_clean_sw_logs_store")?w(f,Mk(a),3):f.u(0);d=f.i;e=O()-2592E6;return w(f,pj(d,["SWHealthLog"],{mode:"readwrite",K:!0},function(g){return yj(g.objectStore("SWHealthLog"),{},function(h){if(h.getValue().timestamp<=e)return h.delete().then(function(){return h.continue()})})}),0)})})}
function Ok(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,Mk(a),2);d=e.i;return w(e,d.clear("SWHealthLog"),0)})})}
;var Pk;function Qk(){Pk||(Pk=new Di("yt.offline"));return Pk}
function Rk(a){if(N("offline_error_handling")){var b=Qk().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Qk().set("errors",b,2592E3,!0)}}
;var Sk=vg("network_polling_interval",3E4);function U(){kf.call(this);this.C=0;this.J=this.l=!1;this.j=this.Ia();Tk(this);Uk(this)}
v(U,kf);function Vk(){if(!U.h){var a=C("yt.networkStatusManager.instance")||new U;A("yt.networkStatusManager.instance",a,void 0);U.h=a}return U.h}
m=U.prototype;m.H=function(){return this.j};
m.aa=function(a,b){a!==this.j&&((void 0===b?0:b)?this.N():this.j=a)};
m.Ib=function(a){this.l=!0;if(void 0===a?0:a)this.C||Wk(this)};
m.Ia=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.ub=function(){this.J=!0};
m.Y=function(a,b){return kf.prototype.Y.call(this,a,b)};
function Uk(a){window.addEventListener("online",function(){return I(a,function c(){var d=this;return x(c,function(e){if(1==e.h)return w(e,d.N(),2);if(d.J&&N("offline_error_handling")){var f=Qk().get("errors",!0);if(f){for(var g in f)if(f[g]){var h=new Pi(g,"sent via offline_errors");h.name=f[g].name;h.stack=f[g].stack;h.level=f[g].level;qg(h)}Qk().set("errors",{},2592E3,!0)}}e.h=0})})})}
function Tk(a){window.addEventListener("offline",function(){return I(a,function c(){var d=this;return x(c,function(e){return w(e,d.N(),0)})})})}
function Wk(a){a.C=Ng(function(){return I(a,function c(){var d=this;return x(c,function(e){if(1==e.h)return d.j?d.Ia()||!d.l?e.u(3):w(e,d.N(),3):w(e,d.N(),3);Wk(d);e.h=0})})},Sk)}
m.N=function(a){var b=this;return this.m?this.m:this.m=new Promise(function(c){return I(b,function e(){var f,g,h,k=this;return x(e,function(l){switch(l.h){case 1:return f=window.AbortController?new window.AbortController:void 0,g=null===f||void 0===f?void 0:f.signal,h=!1,sa(l,2,3),f&&(k.B=Pg(function(){f.abort()},a||2E4)),w(l,fetch("/generate_204",{method:"HEAD",
signal:g}),5);case 5:h=!0;case 3:ua(l);k.m=void 0;k.B&&Sg(k.B);h!==k.j&&(k.j=h,k.j&&k.l?lf(k,"ytnetworkstatus-online"):k.l&&lf(k,"ytnetworkstatus-offline"));c(h);va(l);break;case 2:ta(l),h=!1,l.u(3)}})})})};
U.prototype.sendNetworkCheckRequest=U.prototype.N;U.prototype.listen=U.prototype.Y;U.prototype.enableErrorFlushing=U.prototype.ub;U.prototype.getWindowStatus=U.prototype.Ia;U.prototype.monitorNetworkStatusChange=U.prototype.Ib;U.prototype.networkStatusHint=U.prototype.aa;U.prototype.isNetworkAvailable=U.prototype.H;U.getInstance=Vk;function Xk(a){a=void 0===a?{}:a;kf.call(this);var b=this;this.l=this.B=0;this.j=Vk();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.j);c&&c(a.Ya);a.eb&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.j))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.j))a.Aa?(this.Aa=a.Aa,c("ytnetworkstatus-online",function(){Yk(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){Yk(b,"publicytnetworkstatus-offline")})):
(c("ytnetworkstatus-online",function(){lf(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){lf(b,"publicytnetworkstatus-offline")}))}
v(Xk,kf);Xk.prototype.H=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.j);return a?a():!0};
Xk.prototype.aa=function(a,b){b=void 0===b?!1:b;var c=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);c&&c(a,b)};
Xk.prototype.N=function(a){return I(this,function c(){var d=this,e;return x(c,function(f){return(e=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(d.j))?f.return(e(a)):f.return(!0)})})};
function Yk(a,b){a.Aa?a.l?(Sg(a.B),a.B=Pg(function(){a.m!==b&&(lf(a,b),a.m=b,a.l=O())},a.Aa-(O()-a.l))):(lf(a,b),a.m=b,a.l=O()):lf(a,b)}
;var Zk=!1,$k,al=0,bl=0,cl,dl=z.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Zk,databaseToken:$k,potentialEsfErrorCounter:bl,isIdbSupported:!!$k};A("ytNetworklessLoggingInitializationOptions",dl,void 0);
function el(){I(this,function b(){return x(b,function(c){switch(c.h){case 1:return w(c,Sj(),2);case 2:$k=c.i;if(!$k||!Qi()&&!N("nwl_init_require_datasync_id_killswitch")){c.u(0);break}Zk=!0;dl.isNwlInitialized=Zk;dl.databaseToken=$k;dl.isIdbSupported=!!$k;return w(c,ak("LogsDatabaseV2"),4);case 4:if(!(.1>=Math.random())){c.u(5);break}return w(c,Ik($k),6);case 6:return w(c,Nk($k),5);case 5:fl();gl().H()&&hl();gl().Y("publicytnetworkstatus-online",hl);gl().Y("publicytnetworkstatus-offline",il);if(!N("networkless_immediately_drop_sw_health_store")){c.u(8);
break}return w(c,jl(),8);case 8:if(N("networkless_immediately_drop_all_requests"))return w(c,Jk(),0);c.u(0)}})})}
function kl(a,b){function c(d){var e=gl().H();if(!ll()||!d||e&&N("vss_networkless_bypass_write"))ml(a,b);else{var f={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0};Ck(f,d).then(function(g){f.id=g;gl().H()&&nl(f)}).catch(function(g){nl(f);
gl().H()?qg(g):Rk(g)})}}
b=void 0===b?{}:b;N("skip_is_supported_killswitch")?Sj().then(function(d){c(d)}):c(ol())}
function pl(a,b){function c(d){if(ll()&&d){var e={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(h,k){void 0!==e.id?Hk(e.id,d):f=!0;N("vss_network_hint")&&gl().aa(!0);g(h,k)};
ml(e.url,e.options);Ck(e,d).then(function(h){e.id=h;f&&Hk(e.id,d)}).catch(function(h){gl().H()?qg(h):Rk(h)})}else ml(a,b)}
b=void 0===b?{}:b;N("skip_is_supported_killswitch")?Sj().then(function(d){c(d)}):c(ol())}
function hl(){var a=this,b=ol();if(!b)throw dj("throttleSend");al||(al=Pg(function(){return I(a,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Ek("NEW",b),2);if(3!=f.h)return e=f.i,e?w(f,nl(e),3):(il(),f.return());al&&(al=0,hl());f.h=0})})},100))}
function il(){Sg(al);al=0}
function nl(a){return I(this,function c(){var d,e,f;return x(c,function(g){switch(g.h){case 1:d=ol();if(!d)throw e=dj("immediateSend"),e;if(void 0===a.id){g.u(2);break}return w(g,Fk(a.id,d),3);case 3:(f=g.i)?a=f:rg(Error("The request cannot be found in the database."));case 2:if(ql(a,2592E6)){g.u(4);break}rg(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){g.u(5);break}return w(g,Hk(a.id,d),5);case 5:return g.return();case 4:a.skipRetry||(a=rl(a));var h=a,k,l;
if(null===(l=null===(k=null===h||void 0===h?void 0:h.options)||void 0===k?void 0:k.postParams)||void 0===l?0:l.requestTimeMs)h.options.postParams.requestTimeMs=Math.round(O());a=h;if(!a){g.u(0);break}if(!a.skipRetry||void 0===a.id){g.u(8);break}return w(g,Hk(a.id,d),8);case 8:ml(a.url,a.options,!!a.skipRetry),g.h=0}})})}
function rl(a){var b=this,c=ol();if(!c)throw dj("updateRequestHandlers");var d=a.options.onError?a.options.onError:function(){};
a.options.onError=function(f,g){return I(b,function k(){var l;return x(k,function(n){switch(n.h){case 1:l=ik(g);if(!(N("nwl_consider_error_code")&&l||!N("nwl_consider_error_code")&&sl()<=vg("potential_esf_error_limit",10))){n.u(2);break}return w(n,gl().N(),3);case 3:if(gl().H()){n.u(2);break}d(f,g);if(!N("nwl_consider_error_code")||void 0===(null===a||void 0===a?void 0:a.id)){n.u(5);break}return w(n,Gk(a.id,c,!1),5);case 5:return n.return();case 2:if(N("nwl_consider_error_code")&&!l&&sl()>vg("potential_esf_error_limit",
10))return n.return();C("ytNetworklessLoggingInitializationOptions")&&dl.potentialEsfErrorCounter++;bl++;if(void 0===(null===a||void 0===a?void 0:a.id)){n.u(7);break}return 1>a.sendCount?w(n,Gk(a.id,c),11):w(n,Hk(a.id,c),7);case 11:Pg(function(){gl().H()&&hl()},5E3);
case 7:d(f,g),n.h=0}})})};
var e=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(f,g){return I(b,function k(){return x(k,function(l){if(1==l.h)return void 0===(null===a||void 0===a?void 0:a.id)?l.u(2):w(l,Hk(a.id,c),2);N("vss_network_hint")&&gl().aa(!0);e(f,g);l.h=0})})};
return a}
function ql(a,b){a=a.timestamp;return O()-a>=b?!1:!0}
function fl(){var a=this,b=ol();if(!b)throw dj("retryQueuedRequests");Ek("QUEUED",b).then(function(c){c&&!ql(c,12E4)?Pg(function(){return I(a,function e(){return x(e,function(f){if(1==f.h)return void 0===c.id?f.u(2):w(f,Gk(c.id,b),2);fl();f.h=0})})}):gl().H()&&hl()})}
function jl(){return I(this,function b(){var c,d;return x(b,function(e){c=ol();if(!c)throw d=dj("clearSWHealthLogsDb"),d;return e.return(Ok(c).catch(function(f){qg(f)}))})})}
function gl(){cl||(cl=new Xk({eb:!0,Ya:!0}));return cl}
function ml(a,b,c){if(N("networkless_with_beacon")){var d=["method","postBody"];if(Object.keys(b).length>d.length)c=!0;else{c=0;d=u(d);for(var e=d.next();!e.done;e=d.next())b.hasOwnProperty(e.value)&&c++;c=Object.keys(b).length!==c}c?uh(a,b):Jh(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?Gh(a):uh(a,b)}
function ll(){return C("ytNetworklessLoggingInitializationOptions")?dl.isNwlInitialized:Zk}
function ol(){return C("ytNetworklessLoggingInitializationOptions")?dl.databaseToken:$k}
function sl(){return C("ytNetworklessLoggingInitializationOptions")?dl.potentialEsfErrorCounter:bl}
;function tl(){bk.call(this,{G:{sb:Ik,ia:Hk,ab:Ek,Gb:Fk,Pa:Gk,set:Ck},I:new Xk({eb:!0,Ya:!0}),handleError:qg,ja:rg,S:ul,now:O,ob:Rk,cb:Rg(),Oa:"publicytnetworkstatus-online",Na:"publicytnetworkstatus-offline",va:!0,sa:.1,za:vg("potential_esf_error_limit",10),F:N});this.va&&Math.random()<=this.sa&&this.databaseToken&&Nk(this.databaseToken);N("networkless_immediately_drop_sw_health_store")&&vl(this);N("networkless_immediately_drop_all_requests")&&Jk();ak("LogsDatabaseV2")}
v(tl,bk);function wl(){var a=C("yt.networklessRequestController.instance");a||(a=new tl,A("yt.networklessRequestController.instance",a,void 0),N("networkless_logging")&&Sj().then(function(b){a.databaseToken=b;ck(a)}));
return a}
tl.prototype.writeThenSend=function(a,b){b||(b={});Qi()||(this.h=!1);bk.prototype.writeThenSend.call(this,a,b)};
tl.prototype.sendThenWrite=function(a,b,c){b||(b={});Qi()||(this.h=!1);bk.prototype.sendThenWrite.call(this,a,b,c)};
tl.prototype.sendAndWrite=function(a,b){b||(b={});Qi()||(this.h=!1);bk.prototype.sendAndWrite.call(this,a,b)};
function vl(a){I(a,function c(){var d=this,e,f;return x(c,function(g){e=d;if(!d.databaseToken)throw f=dj("clearSWHealthLogsDb"),f;return g.return(Ok(d.databaseToken).catch(function(h){e.handleError(h)}))})})}
function ul(a,b,c){var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(O());if(N("networkless_with_beacon")){c=b;var e=["method","postBody"];if(Object.keys(c).length>e.length)c=!0;else{d=0;e=u(e);for(var f=e.next();!f.done;f=e.next())c.hasOwnProperty(f.value)&&d++;c=Object.keys(c).length!==d}c?uh(a,b):Jh(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?Gh(a):uh(a,b)}
;function xl(a){var b=this;this.config_=null;a?this.config_=a:Ai()&&(this.config_=ki());Ng(function(){Ii(b)},5E3)}
xl.prototype.isReady=function(){!this.config_&&Ai()&&(this.config_=ki());return!!this.config_};
function ni(a,b,c,d){function e(y){y=void 0===y?!1:y;var B;if(d.retry&&"www.youtube-nocookie.com"!=h&&(y||N("skip_ls_gel_retry")||(B=Gi(b,c,l,k)),B)){var G=g.onSuccess,R=g.onFetchSuccess;g.onSuccess=function(P,K){Hi(B);G(P,K)};
c.onFetchSuccess=function(P,K){Hi(B);R(P,K)}}try{y&&d.retry&&!d.gb.bypassNetworkless?(g.method="POST",d.gb.writeThenSend?N("use_new_nwl")?wl().writeThenSend(q,g):kl(q,g):N("use_new_nwl")?wl().sendAndWrite(q,g):pl(q,g)):(g.method="POST",g.postParams||(g.postParams={}),uh(q,g))}catch(P){if("InvalidAccessError"==P.name)B&&(Hi(B),B=0),rg(Error("An extension is blocking network request."));
else throw P;}B&&Ng(function(){Ii(a)},5E3)}
!F("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&rg(new Pi("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Pi("innertube xhrclient not ready",b,c,d);qg(f);throw f;}var g={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(y,B){if(d.onSuccess)d.onSuccess(B)},
onFetchSuccess:function(y){if(d.onSuccess)d.onSuccess(y)},
onError:function(y,B){if(d.onError)d.onError(B)},
onFetchError:function(y){if(d.onError)d.onError(y)},
timeout:d.timeout,withCredentials:!0},h="";(f=a.config_.Cb)&&(h=f);var k=a.config_.Eb||!1,l=Bi(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},r=a.config_.Db&&f;N("omit_innertube_api_key_for_Bearer_auth_header")&&(r=r&&f.startsWith("Bearer"));r||(p.key=a.config_.innertubeApiKey);var q=ih(""+h+n,p||{},!0);N("use_new_nwl")||ll()?Rj().then(function(y){e(y)}):e(!1)}
;function V(a,b,c){c=void 0===c?{}:c;var d=xl;F("ytLoggingEventsDefaultDisabled",!1)&&xl==xl&&(d=null);pi(a,b,d,c)}
;var yl=[{Ma:function(a){return"Cannot read property '"+a.key+"'"},
ya:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ma:function(a){return"Cannot call '"+a.key+"'"},
ya:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ma:function(a){return a.key+" is not defined"},
ya:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Al={Z:[],V:[{Ta:zl,weight:500}]};function zl(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Bl(){this.V=[];this.Z=[]}
var Cl;function Dl(){if(!Cl){var a=Cl=new Bl;a.Z.length=0;a.V.length=0;Al.Z&&a.Z.push.apply(a.Z,Al.Z);Al.V&&a.V.push.apply(a.V,Al.V)}return Cl}
;var El=new L;function Fl(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Gl(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Gl(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Gl(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Gl(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Hl(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Il(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Fl(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Il(e+".ve",f,g,h):0;d+=g;d+=Il(e,a[e],b,c);if(500<d)break}}else c[b]=Jl(a),d+=c[b].length;else c[b]=Jl(a),d+=c[b].length;return d}
function Il(a,b,c,d){c+="."+a;a=Jl(b);d[c]=a;return c.length+a.length}
function Jl(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
;var Kl=new Set,Ll=0,Ml=0,Nl=0,Ol=[],Pl=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Ql(a){Rl(a,"WARNING")}
function Rl(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||F("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),N("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+
a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=Ll))){var g=ne(a);d=g.message||"Unknown Error";e=g.name||"UnknownError";var h=g.stack||a.i||"Not available";h.startsWith(e+": "+d)&&(f=h.split("\n"),f.shift(),h=f.join("\n"));f=g.lineNumber||"Not available";g=g.fileName||"Not available";var k=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var l=0;l<a.args.length&&!(k=Hl(a.args[l],"params."+l,c,k),500<=k);l++);else if(a.hasOwnProperty("params")&&a.params){var n=
a.params;if("object"===typeof a.params)for(l in n){if(n[l]){var p="params."+l,r=Jl(n[l]);c[p]=r;k+=p.length+r.length;if(500<k)break}}else c.params=Jl(n)}if(Ol.length)for(l=0;l<Ol.length&&!(k=Hl(Ol[l],"params.context."+l,c,k),500<=k);l++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);l={message:d,name:e,lineNumber:f,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(l.lineNumber=l.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=
Dl();c=u(a.Z);for(d=c.next();!d.done;d=c.next())if(d=d.value,l.message&&l.message.match(d.Lm)){a=d.weight;break a}a=u(a.V);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Ta(l)){a=c.weight;break a}a=1}l.sampleWeight=a;a=u(yl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.ya[l.name])for(e=u(c.ya[l.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=l.message.match(f.regexp)){l.params["params.error.original"]=d[0];e=f.groups;f={};for(g=0;g<e.length;g++)f[e[g]]=d[g+1],l.params["params.error."+e[g]]=
d[g+1];l.message=c.Ma(f);break}l.params||(l.params={});a=Dl();l.params["params.errorServiceSignature"]="msg="+a.Z.length+"&cb="+a.V.length;l.params["params.serviceWorker"]="false";z.document&&z.document.querySelectorAll&&(l.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));vb("sample").constructor!==tb&&(l.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(l);if(0!==l.sampleWeight&&!Kl.has(l.message)){"ERROR"===b?(El.da("handleError",
l),N("record_app_crashed_web")&&0===Nl&&1===l.sampleWeight&&(Nl++,V("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),Ml++):"WARNING"===b&&El.da("handleWarning",l);if(N("kevlar_gel_error_routing")){a=b;b:{c=u(Pl);for(d=c.next();!d.done;d=c.next())if(Dh(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:l.stack};l.fileName&&(d.filename=l.fileName);c=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?2!==c.length||
isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};e={pageUrl:window.location.href,kvPairs:[]};F("FEXP_EXPERIMENTS")&&(e.experimentIds=F("FEXP_EXPERIMENTS"));f=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",
void 0);g=lg.EXPERIMENT_FLAGS;if((!g||!g.web_disable_gel_stp_ecatcher_killswitch)&&f)for(h=u(Object.keys(f)),g=h.next();!g.done;g=h.next())g=g.value,e.kvPairs.push({key:g,value:String(f[g])});if(f=l.params)for(h=u(Object.keys(f)),g=h.next();!g.done;g=h.next())g=g.value,e.kvPairs.push({key:"client."+g,value:String(f[g])});f=F("SERVER_NAME",void 0);g=F("SERVER_VERSION",void 0);f&&g&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:g}));c={errorMetadata:e,stackTrace:d,
logMessage:c}}c&&(V("clientError",c),("ERROR"===a||N("errors_flush_gel_always_killswitch"))&&fi())}if(!N("suppress_error_204_logging")){a=l.params||{};b={urlParams:{a:"logerror",t:"jserror",type:l.name,msg:l.message.substr(0,250),line:l.lineNumber,level:b,"client.name":a.name},postParams:{url:F("PAGE_NAME",window.location.href),file:l.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){l.stack&&(b.postParams.stack=l.stack);c=u(Object.keys(a));for(d=c.next();!d.done;d=
c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=u(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=F("SERVER_NAME",void 0);c=F("SERVER_VERSION",void 0);a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}uh(F("ECATCHER_REPORT_HOST","")+"/error_204",b)}try{Kl.add(l.message)}catch(q){}Ll++}}}
function Sl(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];a.args||(a.args=[]);a.args.push.apply(a.args,ha(c))}
;var Tl={Lc:3611,Yb:27686,Zb:85013,ac:23462,dc:42016,ec:62407,fc:26926,cc:43781,hc:51236,ic:79148,jc:50160,kc:77504,yc:87907,zc:18630,Ac:54445,Bc:80935,Cc:105675,Dc:37521,Ec:47786,Fc:98349,Gc:123695,Hc:6827,Ic:29434,Jc:7282,Kc:124448,Oc:32276,Nc:76278,Pc:93911,Qc:106531,Rc:27259,Sc:27262,Tc:27263,Vc:21759,Wc:27107,Xc:62936,Yc:49568,Zc:38408,bd:80637,cd:68727,dd:68728,ed:80353,fd:80356,gd:74610,hd:45707,jd:83962,kd:83970,ld:46713,md:89711,nd:74612,od:93265,pd:74611,qd:131380,sd:128979,td:128978,rd:131391,
ud:105350,wd:134800,vd:131392,yd:113533,zd:93252,Ad:99357,Cd:94521,Dd:114252,Ed:113532,Fd:94522,Bd:94583,Gd:88E3,Hd:93253,Id:93254,Jd:94387,Kd:94388,Ld:93255,Md:97424,xd:72502,Nd:110111,Od:76019,Qd:117092,Rd:117093,Pd:89431,Sd:110466,Td:77240,Ud:60508,Vd:137401,Wd:137402,Xd:137046,Yd:73393,Zd:113534,ae:92098,be:131381,ce:84517,de:83759,ee:80357,ge:86113,he:72598,ie:72733,je:107349,ke:124275,le:118203,me:133275,ne:133274,oe:133272,pe:133273,qe:133276,se:117431,re:133797,te:128572,ue:133405,we:117429,
xe:117430,ye:117432,ze:120080,Ae:117259,Be:121692,Ce:132972,De:133051,Ee:133658,Fe:132971,Ge:97615,He:31402,Je:133624,Ke:133623,Le:133622,Ie:133621,Me:84774,Ne:95117,Oe:98930,Pe:98931,Qe:98932,Re:43347,Se:129889,Te:45474,Ue:100352,Ve:84758,We:98443,Xe:117985,Ye:74613,Ze:74614,af:64502,bf:136032,cf:74615,df:74616,ef:122224,ff:74617,gf:77820,hf:74618,jf:93278,kf:93274,lf:93275,mf:93276,nf:22110,pf:29433,qf:133798,rf:132295,tf:120541,vf:82047,wf:113550,xf:75836,yf:75837,zf:42352,Af:84512,Bf:76065,Cf:75989,
Df:16623,Ef:32594,Ff:27240,Gf:32633,Hf:74858,Jf:3945,If:16989,Kf:45520,Lf:25488,Mf:25492,Nf:25494,Of:55760,Pf:14057,Qf:18451,Rf:57204,Sf:57203,Tf:17897,Uf:57205,Vf:18198,Wf:17898,Xf:17909,Yf:43980,Zf:46220,ag:11721,cg:49954,dg:96369,eg:3854,fg:56251,gg:25624,hg:16906,ig:99999,jg:68172,kg:27068,lg:47973,mg:72773,ng:26970,og:26971,pg:96805,qg:17752,rg:73233,sg:109512,tg:22256,ug:14115,vg:22696,wg:89278,xg:89277,yg:109513,zg:43278,Ag:43459,Bg:43464,Cg:89279,Dg:43717,Eg:55764,Fg:22255,Gg:89281,Hg:40963,
Ig:43277,Jg:43442,Kg:91824,Lg:120137,Mg:96367,Ng:36850,Og:72694,Pg:37414,Qg:36851,Sg:124863,Rg:121343,Tg:73491,Ug:54473,Vg:43375,Wg:46674,Xg:32473,Yg:72901,Zg:72906,ah:50947,bh:50612,dh:50613,eh:50942,fh:84938,gh:84943,hh:84939,ih:84941,jh:84944,kh:84940,lh:84942,mh:35585,nh:51926,oh:79983,ph:63238,qh:18921,rh:63241,sh:57893,th:41182,uh:135732,vh:33424,wh:22207,xh:42993,yh:36229,zh:22206,Ah:22205,Bh:18993,Ch:19001,Dh:18990,Eh:18991,Fh:18997,Gh:18725,Hh:19003,Ih:36874,Jh:44763,Kh:33427,Lh:67793,Mh:22182,
Nh:37091,Oh:34650,Ph:50617,Qh:47261,Rh:22287,Sh:25144,Th:97917,Uh:62397,Vh:125598,Wh:137935,Xh:36961,Yh:108035,Zh:27426,ai:27857,bi:27846,ci:27854,di:69692,fi:61411,gi:39299,hi:38696,ii:62520,ji:36382,ki:108701,li:50663,mi:36387,ni:14908,oi:37533,ri:105443,si:61635,ti:62274,vi:133818,wi:65702,xi:65703,yi:65701,zi:76256,Ai:37671,Bi:49953,Di:36216,Ei:28237,Fi:39553,Gi:29222,Hi:26107,Ii:38050,Ji:26108,Li:120745,Ki:26109,Mi:26110,Ni:66881,Oi:28236,Pi:14586,Qi:57929,Ri:74723,Si:44098,Ti:44099,Wi:23528,
Xi:61699,Ui:134104,Vi:134103,Yi:59149,Zi:101951,aj:97346,bj:118051,cj:95102,dj:64882,ej:119505,fj:63595,gj:63349,hj:95101,ij:75240,jj:27039,kj:68823,lj:21537,mj:83464,nj:75707,oj:83113,pj:101952,qj:101953,sj:79610,tj:125755,uj:24402,vj:24400,wj:32925,xj:57173,yj:122502,zj:64423,Aj:64424,Bj:33986,Cj:100828,Dj:129089,Ej:21409,Ij:135155,Jj:135156,Kj:135157,Lj:135158,Mj:135159,Nj:135160,Oj:135161,Pj:135162,Qj:135163,Rj:135164,Sj:135165,Tj:135166,Fj:11070,Gj:11074,Hj:17880,Uj:14001,Wj:30709,Xj:30707,Yj:30711,
Zj:30710,ak:30708,Vj:26984,bk:63648,ck:63649,dk:51879,ek:111059,fk:5754,gk:20445,ik:130975,hk:130976,jk:110386,kk:113746,lk:66557,mk:17310,nk:28631,pk:21589,qk:68012,rk:60480,sk:31571,tk:76980,uk:41577,vk:45469,wk:38669,xk:13768,yk:13777,zk:62985,Ak:4724,Bk:59369,Ck:43927,Dk:43928,Ek:12924,Fk:100355,Ik:56219,Jk:27669,Kk:10337,Hk:47896,Lk:122629,Mk:121258,Nk:107598,Ok:127991,Pk:96639,Qk:107536,Rk:130169,Sk:96661,Tk:96658,Uk:116646,Vk:121122,Wk:96660,Xk:127738,Yk:127083,Zk:104443,al:96659,bl:106442,
dl:134840,fl:63667,il:63668,jl:63669,kl:130686,ll:78314,ml:55761,nl:127098,ol:134841,pl:96368,ql:67374,rl:48992,sl:49956,ul:31961,vl:26388,wl:23811,xl:5E4,yl:126250,zl:96370,Al:47355,Bl:47356,Cl:37935,Dl:45521,El:21760,Fl:83769,Gl:49977,Hl:49974,Il:93497,Jl:93498,Kl:34325,Ll:115803,Ml:123707,Nl:100081,Ol:35309,Pl:68314,Ql:25602,Rl:100339,Sl:59018,Tl:18248,Ul:50625,Vl:9729,Wl:37168,Xl:37169,Yl:21667,Zl:16749,am:18635,bm:39305,cm:18046,dm:53969,em:8213,fm:93926,gm:102852,hm:110099,im:22678,jm:69076,
km:137575,mm:100856,nm:17736,om:3832,pm:55759,qm:64031,rm:93044,sm:93045,tm:34388,um:17657,vm:17655,wm:39579,xm:39578,ym:77448,zm:8196,Am:11357,Bm:69877,Cm:8197,Dm:82039};function Ul(){var a=nb(Vl),b;return Df(new wf(function(c,d){a.onSuccess=function(e){oh(e)?c(new Wl(e)):d(new Xl("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Xl("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Xl("Request timed out","net.timeout",e))};
b=uh("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Ff&&b.abort();
return Bf(c)})}
function Xl(a,b,c){Wa.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(Xl,Wa);function Wl(a){this.xhr=a}
;function Yl(){this.i=0;this.h=null}
Yl.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),vf(a)?a:Zl(a)):2===this.i&&b?(a=b.call(c,this.h),vf(a)?a:$l(a)):this};
Yl.prototype.getValue=function(){return this.h};
Yl.prototype.$goog_Thenable=!0;function $l(a){var b=new Yl;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function Zl(a){var b=new Yl;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function am(){if(Qd())return!0;var a=F("INNERTUBE_CLIENT_NAME");return!a||"WEB"!==a&&"MWEB"!==a||Ch&&Dh("applewebkit")&&!Dh("version")&&(!Dh("safari")||Dh("gsa/"))||tc&&Dh("version/")?!0:(a=Od.get("CONSENT",void 0))?a.startsWith("YES+"):!0}
;function bm(a){Wa.call(this,a.message||a.description||a.name);this.isMissing=a instanceof cm;this.isTimeout=a instanceof Xl&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Ff}
v(bm,Wa);bm.prototype.name="BiscottiError";function cm(){Wa.call(this,"Biscotti ID is missing from server")}
v(cm,Wa);cm.prototype.name="BiscottiMissingError";var Vl={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},dm=null;function Zg(){if(N("disable_biscotti_fetch_entirely_for_all_web_clients"))return Bf(Error("Biscotti id fetching has been disabled entirely."));if(!am())return Bf(Error("User has not consented - not fetching biscotti id."));if("1"==lb())return Bf(Error("Biscotti ID is not available in private embed mode"));dm||(dm=Df(Ul().then(em),function(a){return fm(2,a)}));
return dm}
function em(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new cm;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new cm;a=a.id;$g(a);dm=Zl(a);gm(18E5,2);return a}
function fm(a,b){b=new bm(b);$g("");dm=$l(b);0<a&&gm(12E4,a-1);throw b;}
function gm(a,b){Jg(function(){Df(Ul().then(em,function(c){return fm(b,c)}),Ha)},a)}
function hm(){try{var a=C("yt.ads.biscotti.getId_");return a?a():Zg()}catch(b){return Bf(b)}}
;function im(a){if("1"!=lb()){a&&Yg();try{hm().then(function(){},function(){}),Jg(im,18E5)}catch(b){qg(b)}}}
;var jm=Date.now().toString();
function km(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(jm)for(a=1,b=0;b<jm.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^jm.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var lm,mm=z.ytLoggingDocDocumentNonce_;mm||(mm=km(),Ua("ytLoggingDocDocumentNonce_",mm));lm=mm;var nm={sf:0,Mc:1,Uc:2,Ci:3,uf:4,lm:5,rj:6,Gk:7,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE"};function om(a){this.h=a}
function pm(a){return new om({trackingParams:a})}
om.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
om.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
om.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function qm(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function rm(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function sm(a){return F(rm(void 0===a?0:a),void 0)}
A("yt_logging_screen.getRootVeType",sm,void 0);function tm(a){return(a=sm(void 0===a?0:a))?new om({veType:a,youtubeData:void 0}):null}
function um(){var a=F("csn-to-ctt-auth-info");a||(a={},M("csn-to-ctt-auth-info",a));return a}
function vm(a){a=void 0===a?0:a;var b=F(qm(a));if(!b&&!F("USE_CSN_FALLBACK",!0))return null;b||!N("use_undefined_csn_any_layer")&&0!=a||(b="UNDEFINED_CSN");return b?b:null}
A("yt_logging_screen.getCurrentCsn",vm,void 0);function wm(a,b,c){var d=um();(c=vm(c))&&delete d[c];b&&(d[a]=b)}
function xm(a){return um()[a]}
A("yt_logging_screen.getCttAuthInfo",xm,void 0);function ym(a,b,c,d){c=void 0===c?0:c;if(a!==F(qm(c))||b!==F(rm(c)))wm(a,d,c),M(qm(c),a),M(rm(c),b),b=function(){setTimeout(function(){a&&pi("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:lm,clientScreenNonce:a},xl)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
A("yt_logging_screen.setCurrentScreen",ym,void 0);function zm(a){jk.call(this,1,arguments);this.csn=a}
v(zm,jk);var sk=new kk("screen-created",zm),Am=[],Cm=Bm,Dm=0;function Em(a,b,c,d){var e=d.filter(function(f){f.csn!==b?(f.csn=b,f=!0):f=!1;return f});
c={csn:b,parentVe:c.getAsJson(),childVes:ab(e,function(f){return f.getAsJson()})};
d=u(d);for(e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(jb(e)||!e.trackingParams&&!e.veType)&&Ql(Error("Child VE logged with no data"));d={cttAuthInfo:xm(b),ba:b};"UNDEFINED_CSN"==b?Fm("visualElementAttached",c,d):a?pi("visualElementAttached",c,a,d):V("visualElementAttached",c,d)}
function Bm(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return Ic(b,3)}
function Fm(a,b,c){Am.push({payloadName:a,payload:b,options:c});Dm||(Dm=tk())}
function uk(a){if(Am){for(var b=u(Am),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,pi(c.payloadName,c.payload,null,c.options));Am.length=0}Dm=0}
;function Gm(){this.i=new Set;this.h=new Set;this.j=new Map}
Gm.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
Ia(Gm);function Hm(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!Im(a)||c.some(function(e){return!Im(e)}))throw Error("Only objects may be merged.");
c=u(c);for(d=c.next();!d.done;d=c.next())Jm(a,d.value);return a}
function Jm(a,b){for(var c in b)if(Im(b[c])){if(c in a&&!Im(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Jm(a[c],b[c])}else if(Km(b[c])){if(c in a&&!Km(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Lm(a[c],b[c])}else a[c]=b[c];return a}
function Lm(a,b){b=u(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Im(c)?a.push(Jm({},c)):Km(c)?a.push(Lm([],c)):a.push(c);return a}
function Im(a){return"object"===typeof a&&!Array.isArray(a)}
function Km(a){return"object"===typeof a&&Array.isArray(a)}
;function Mm(a,b){jk.call(this,1,arguments)}
v(Mm,jk);function Nm(a,b){jk.call(this,1,arguments)}
v(Nm,jk);var Om=new kk("aft-recorded",Mm),Pm=new kk("timing-sent",Nm);var Qm=window;function Rm(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var W=Qm.performance||Qm.mozPerformance||Qm.msPerformance||Qm.webkitPerformance||new Rm;var Sm=!1,Tm={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Sa(W.clearResourceTimings||W.webkitClearResourceTimings||W.mozClearResourceTimings||W.msClearResourceTimings||W.oClearResourceTimings||Ha,W);function Um(a){var b=Vm(a);if(b.aft)return b.aft;a=F((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function Wm(){var a;if(N("csi_use_performance_navigation_timing")){var b,c,d,e=null===(d=null===(c=null===(b=null===(a=null===W||void 0===W?void 0:W.getEntriesByType)||void 0===a?void 0:a.call(W,"navigation"))||void 0===b?void 0:b[0])||void 0===c?void 0:c.toJSON)||void 0===d?void 0:d.call(c);e?(e.requestStart=Xm(e.requestStart),e.responseEnd=Xm(e.responseEnd),e.redirectStart=Xm(e.redirectStart),e.redirectEnd=Xm(e.redirectEnd),e.domainLookupEnd=Xm(e.domainLookupEnd),e.connectStart=Xm(e.connectStart),
e.connectEnd=Xm(e.connectEnd),e.responseStart=Xm(e.responseStart),e.secureConnectionStart=Xm(e.secureConnectionStart),e.domainLookupStart=Xm(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=W.timing}else a=W.timing;return a}
function Ym(){return N("csi_use_time_origin")&&W.timeOrigin?Math.floor(W.timeOrigin):W.timing.navigationStart}
function Xm(a){return Math.round(Ym()+a)}
function Zm(a){var b;(b=C("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Ua("ytcsi."+(a||"")+"data_",b));return b}
function $m(a){a=Zm(a);a.info||(a.info={});return a.info}
function Vm(a){a=Zm(a);a.tick||(a.tick={});return a.tick}
function an(a){var b=Zm(a).nonce;b||(b=km(),Zm(a).nonce=b);return b}
function bn(a){var b=Vm(a||""),c=Um(a);c&&!Sm&&(pk(Om,new Mm(Math.round(c-b._start),a)),Sm=!0)}
;function cn(){if(W.getEntriesByType){var a=W.getEntriesByType("paint");if(a=cb(a,function(b){return"first-paint"===b.name}))return Xm(a.startTime)}a=W.timing;
return a.Jb?Math.max(0,a.Jb):0}
;function dn(){var a=C("ytcsi.debug");a||(a=[],A("ytcsi.debug",a,void 0),A("ytcsi.reference",{},void 0));return a}
function en(a){a=a||"";var b=C("ytcsi.reference");b||(dn(),b=C("ytcsi.reference"));if(b[a])return b[a];var c=dn(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var gn=z.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",gn,void 0);function hn(){this.h=0}
function jn(){hn.h||(hn.h=new hn);return hn.h}
hn.prototype.tick=function(a,b,c,d){kn(this,"tick_"+a+"_"+b)||V("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
hn.prototype.info=function(a,b,c){var d=Object.keys(a).join("");kn(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,V("latencyActionInfo",a,{cttAuthInfo:c}))};
hn.prototype.span=function(a,b,c){var d=Object.keys(a).join("");kn(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,V("latencyActionSpan",a,{cttAuthInfo:c}))};
function kn(a,b){gn[b]=gn[b]||{count:0};var c=gn[b];c.count++;c.time=O();a.h||(a.h=Ng(function(){var d=O(),e;for(e in gn)gn[e]&&6E4<d-gn[e].time&&delete gn[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Pi("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Ql(c)),!0):!1}
;var X={},ln=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X.browse="LATENCY_ACTION_BROWSE",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard=
"LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.playlists"]=
"LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf=
"LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard=
"LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest=
"LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X),Y={},mn=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an=
"adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cs="commandSource",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",
Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.ncnp="webInfo.nonPreloadedNodeCount",Y.pnt="performanceNavigationTiming",
Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs=
"tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",
Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),nn="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),on={},pn=(on.ccs="CANARY_STATE_",
on.mver="MEASUREMENT_VERSION_",on.pis="PLAYER_INITIALIZED_STATE_",on.yt_pt="LATENCY_PLAYER_",on.pa="LATENCY_ACTION_",on.ctop="TOP_ENTITY_TYPE_",on.yt_vst="VIDEO_STREAM_TYPE_",on),qn="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function rn(a){return!!F("FORCE_CSI_ON_GEL",!1)||N("csi_on_gel")||N("enable_csi_on_gel")||N("unplugged_tvhtml5_csi_on_gel")||!!Zm(a).useGel}
function sn(a,b,c){var d=tn(c);d.gelTicks&&(d.gelTicks["tick_"+a]=!0);c||b||O();if(rn(c)){en(c||"").tick[a]=b||O();d=an(c);var e=Zm(c).cttAuthInfo;"_start"===a?(a=jn(),kn(a,"baseline_"+d)||V("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:e})):jn().tick(a,d,b,e);bn(c);return!0}return!1}
function un(a,b,c){c=tn(c);if(c.gelInfos)c.gelInfos["info_"+a]=!0;else{var d={};c.gelInfos=(d["info_"+a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in mn){c=mn[a];0<=Za(nn,c)&&(b=!!b);a in pn&&"string"===typeof b&&(b=pn[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Hm({},d)}0<=Za(qn,a)||Ql(new Pi("Unknown label logged with GEL CSI",a))}
function tn(a){a=Zm(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function vn(a){a=tn(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
;function wn(a,b,c){null!==b&&($m(c)[a]=b,rn(c)?(a=un(a,b,c))&&rn(c)&&(b=en(c||""),Hm(b.info,a),Hm(vn(c),a),b=an(c),c=Zm(c).cttAuthInfo,jn().info(a,b,c)):en(c||"").info[a]=b)}
function Z(a,b,c){var d=Vm(c);if(!b&&"_"!==a[0]){var e=a;W.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),W.mark(e))}e=b||O();d[a]=e;sn(a,b,c)||c||(xn(),en("").tick[a]=b||O());return d[a]}
function yn(){var a=an(void 0);requestAnimationFrame(function(){setTimeout(function(){a===an(void 0)&&Z("ol",void 0,void 0)},0)})}
function xn(){if(!C("yt.timing.pingSent_")){var a=F("TIMING_ACTION",void 0),b=Vm();if(a=!!C("ytglobal.timingready_")&&a)a="_start"in Vm(void 0);if(a&&Um()){bn();a=!0;var c=F("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in b)){a=!1;break}if(a&&!rn()){c=Vm();d=$m();e=c._start;var f=F("CSI_SERVICE_NAME","youtube");a={v:2,s:f,action:F("TIMING_ACTION",void 0)};b=d.srt;void 0!==c.srt&&delete d.srt;c.aft=Um();var g=Vm(void 0),h=g.pbr,k=g.vc;g=g.pbs;h&&k&&g&&h<k&&k<g&&$m(void 0).yt_pvis&&
"youtube"===f&&(wn("yt_lt","hot_bg"),f=c.vc,h=c.pbs,delete c.aft,d.aft=Math.round(h-f));for(var l in d)"_"!==l.charAt(0)&&(a[l]=d[l]);c.ps=O();l={};f=[];for(var n in c)"_"!==n.charAt(0)&&(h=Math.round(c[n]-e),l[n]=h,f.push(n+"."+h));a.rt=f.join(",");n=!!d.ap;c="";for(var p in a)a.hasOwnProperty(p)&&(c+="&"+p+"="+a[p]);p="/csi_204?"+c.substring(1);window.navigator&&n?Jh(p):Gh(p);A("yt.timing.pingSent_",!0,void 0);pk(Pm,new Nm(l.aft+(Number(b)||0)))}}}}
function zn(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=zg+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function An(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);cc()&&a.setAttribute("nonce",cc());return c?(a=W.getEntriesByName(c))&&a[0]&&(a=a[0],c=Ym(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Bn(){var a=window.location.protocol,b=W.getEntriesByType("resource");b=$a(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=bb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",Xm(b.startTime)),Z("wffe",Xm(b.responseEnd)))}
var Cn=window;Cn.ytcsi&&(Cn.ytcsi.info=wn,Cn.ytcsi.tick=Z);function Dn(){this.o=[];this.A=[];this.h=[];this.l=[];this.m=[];this.i=new Set;this.B=new Map}
function En(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=vm(c),h=tm(c);g&&h&&((null===(e=d.response)||void 0===e?0:e.trackingParams)&&Em(a.client,g,h,[pm(d.response.trackingParams)]),(null===(f=d.playerResponse)||void 0===f?0:f.trackingParams)&&Em(a.client,g,h,[pm(d.playerResponse.trackingParams)]))})}
function Fn(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.o.push([b,c]);else{var e=vm(d);c=c||tm(d);e&&c&&Em(a.client,e,c,[b])}}
Dn.prototype.clickCommand=function(a,b,c){a=a.clickTrackingParams;c=void 0===c?0:c;if(a)if(c=vm(void 0===c?0:c)){var d=this.client;var e="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";a={csn:c,ve:pm(a).getAsJson(),gestureType:e};b&&(a.clientData=b);b={cttAuthInfo:xm(c),ba:c};"UNDEFINED_CSN"==c?Fm("visualElementGestured",a,b):d?pi("visualElementGestured",a,d,b):V("visualElementGestured",a,b);b=!0}else b=!1;else b=!1;return b};
function Gn(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Hn(a,b,c);var f=tm(c.layer);if(f){for(var g=u(a.o),h=g.next();!h.done;h=g.next())h=h.value,Fn(a,h[0],h[1]||f,c.layer);f=u(a.A);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=vm(g);var l=k[0]||tm(g);h&&l&&(g=a.client,k=k[1],k={csn:h,ve:l.getAsJson(),clientData:k},l={cttAuthInfo:xm(h),ba:h},"UNDEFINED_CSN"==h?Fm("visualElementStateChanged",k,l):g?pi("visualElementStateChanged",k,g,l):V("visualElementStateChanged",
k,l))}}};
vm(c.layer)||a.j();if(c.Xa)for(var d=u(c.Xa),e=d.next();!e.done;e=d.next())En(a,e.value,c.layer);else Rl(Error("Delayed screen needs a data promise."))}
function Hn(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Kb?c.Kb:c.layer;var e=vm(d);d=tm(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=F("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=a.client;h=f;var l=c.Wa,n=c.cttAuthInfo,p=c.Jm,r=Cm(),q={csn:r,pageVe:(new om({veType:b,youtubeData:g})).getAsJson()};h&&h.visualElement?(q.implicitGesture=
{parentCsn:h.clientScreenNonce,gesturedVe:h.visualElement.getAsJson()},p&&(q.implicitGesture.gestureType=p)):h&&Ql(new Pi("newScreen() parent element does not have a VE - rootVe",b));l&&(q.cloneCsn=l);l={cttAuthInfo:n,ba:r};k?pi("screenCreated",q,k,l):V("screenCreated",q,l);pk(sk,new zm(r));var y=r}catch(B){Sl(B,{Om:b,rootVe:d,parentVisualElement:void 0,Im:e,Nm:f,Wa:c.Wa});Rl(B);return}ym(y,b,c.layer,c.cttAuthInfo);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=N("screen_manager_skip_hide_killswitch"))){a:{b=
u(Object.values(nm));for(f=b.next();!f.done;f=b.next())if(vm(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,f=!0,k=(f=void 0===f?!1:f)?16:8,d={csn:e,ve:d.getAsJson(),eventType:k},f={cttAuthInfo:xm(e),ba:e,wb:f},"UNDEFINED_CSN"==e?Fm("visualElementHidden",d,f):b?pi("visualElementHidden",d,b,f):V("visualElementHidden",d,f));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=y||"");wn("csn",y);Gm.getInstance().clear();d=tm(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(N("web_mark_root_visible")||
N("music_web_mark_root_visible"))&&(e=y,y={csn:e,ve:d.getAsJson(),eventType:1},b={cttAuthInfo:xm(e),ba:e},"UNDEFINED_CSN"==e?Fm("visualElementShown",y,b):V("visualElementShown",y,b));a.i.delete(c.layer||0);a.j=void 0;e=u(a.B);for(y=e.next();!y.done;y=e.next())b=u(y.value),y=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Fn(a,y,d,c.layer);for(c=0;c<a.l.length;c++){e=a.l[c];try{e()}catch(B){Rl(B)}}for(c=a.l.length=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(B){Rl(B)}}}
;function In(a){a&&(a.dataset?a.dataset[Jn("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Kn(a,b){return a?a.dataset?a.dataset[Jn(b)]:a.getAttribute("data-"+b):null}
var Ln={};function Jn(a){return Ln[a]||(Ln[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Mn=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Nn=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function On(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Mn,""),c=c.replace(Nn,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Pn(a,b,c)}
function Pn(a,b,c){c=void 0===c?null:c;var d=Qn(a),e=document.getElementById(d),f=e&&Kn(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Oh(d,b),b=""+Ma(b),Rn[b]=f),g||(e=Sn(a,d,function(){Kn(e,"loaded")||(In(e),Rh(d),Jg(Ta(Sh,d),0))},c)))}
function Sn(a,b,c,d){d=void 0===d?null:d;var e=wd(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);pd(e,nf(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Tn(a){a=Qn(a);var b=document.getElementById(a);b&&(Sh(a),b.parentNode.removeChild(b))}
function Un(a,b){a&&b&&(a=""+Ma(b),(a=Rn[a])&&Qh(a))}
function Qn(a){var b=document.createElement("a");$b(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+ec(a)}
var Rn={};var Vn=[],Wn=!1;function Xn(){if(!N("disable_biscotti_fetch_for_ad_blocker_detection")&&!N("disable_biscotti_fetch_entirely_for_all_web_clients")&&am()&&"1"!=lb()){var a=function(){Wn=!0;"google_ad_status"in window?M("DCLKSTAT",1):M("DCLKSTAT",2)};
try{On("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Vn.push(Pg(function(){if(!(Wn||"google_ad_status"in window)){try{Un("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Wn=!0;M("DCLKSTAT",3)}},5E3))}}
function Yn(){var a=Number(F("DCLKSTAT",0));return isNaN(a)?0:a}
;function Zn(){this.i=!1;this.h=null}
Zn.prototype.initialize=function(a,b,c,d){d=void 0===d?!1:d;var e,f;if(a.program){var g=null!==(e=a.interpreterScript)&&void 0!==e?e:null,h=null!==(f=a.interpreterUrl)&&void 0!==f?f:null;if(a.interpreterSafeScript){g=a.interpreterSafeScript;vb("From proto message. b/166824318");g=g.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var k=sb();g=k?k.createScript(g):g;g=(new xb(g)).toString()}a.interpreterSafeUrl&&(h=a.interpreterSafeUrl,vb("From proto message. b/166824318"),h=Bb(h.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||
"").toString());$n(this,g,h,a.program,b,c,d)}else Ql(Error("Cannot initialize botguard without program"))};
function $n(a,b,c,d,e,f,g){g=void 0===g?!1:g;c?(a.i=!0,On(c,function(){a.i=!1;var h=0<=c.indexOf("/th/");(h?window.trayride:window.botguard)?ao(a,d,!!g,h,e):(Tn(c),Ql(new Pi("Unable to load Botguard","from "+c)))},f)):b&&(f=wd(document,"SCRIPT"),f.textContent=b,f.nonce=cc(),document.head.appendChild(f),document.head.removeChild(f),((b=b.includes("trayride"))?window.trayride:window.botguard)?ao(a,d,!!g,b,e):Ql(Error("Unable to load Botguard from JS")))}
function ao(a,b,c,d,e){var f,g;if(d=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{bo(a,new d(b,e?function(){return e(b)}:Ha))}catch(h){h instanceof Error&&Ql(h)}else{try{bo(a,new d(b))}catch(h){h instanceof Error&&Ql(h)}e&&e(b)}else Ql(Error("Failed to finish initializing VM"))}
Zn.prototype.invoke=function(a){a=void 0===a?{}:a;return this.h?this.h.hasOwnProperty("hot")?this.h.hot(void 0,void 0,a):this.h.invoke(void 0,void 0,a):null};
Zn.prototype.dispose=function(){this.h=null};
function bo(a,b){a.h=b}
;var co=new Zn;function eo(){return!!co.h}
function fo(a){a=void 0===a?{}:a;return co.invoke(a)}
;var go=window,ho=/[A-Za-z]+\/[0-9.]+/g;function io(a,b){if(a.replace(ho,"")!==b.replace(ho,""))return!1;a=a.match(ho);b=b.match(ho);if(a.length!==b.length)return!1;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(!d.startsWith(e)&&!e.startsWith(d))return!1}return!0}
function jo(){var a=go.uaChPolyfill.state;if(0===a.type)V("clientHintsPolyfillEvent",{clientHintsSupported:!1});else{var b=navigator.userAgent,c=void 0!==a.syntheticUa&&io(a.syntheticUa,b),d={clientHintsSupported:!0,uaAccessedBeforePolyfill:a.didAccessUaBeforePolyfillAvailable,syntheticUaMatches:c};a.didAccessUaBeforePolyfillAvailable&&(d.uaAccessBeforePolyfillCount=a.uaAccessBeforePolyfillCount,a.firstAccessUaError&&(d.firstUaAccessStack=String(a.firstAccessUaError.stack).replace(/\n/g,""),Rl(a.firstAccessUaError)),
d.polyfillAvailabilityDelayMs=a.polyfillAvailabilityDelay);V("clientHintsPolyfillEvent",d);c||(b={syntheticUa:a.syntheticUa,ua:b},b.brand=a.data.brands.map(function(e){return'"'+e.brand+'"; v="'+e.version+'"'}),b.mobileness=a.data.mobile,a=a.data.values,a.architecture&&(b.platformArchitecture=a.architecture),a.model&&(b.model=a.model),a.platform&&(b.platformBrand=a.platform),a.platformVersion&&(b.platformVersion=a.platformVersion),a.uaFullVersion&&(b.fullVersion=a.uaFullVersion),V("clientHintsPolyfillDiagnostics",
b))}}
var ko=!1;function lo(){var a;1===(null===(a=go.uaChPolyfill)||void 0===a?void 0:a.state.type)?ko||(go.uaChPolyfill.onReady=lo,ko=!0):go.uaChPolyfill&&jo()}
;function mo(a,b,c){J.call(this);var d=this;c=c||F("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.C="*";this.l=c;this.sessionId=null;this.channel="widget";this.J=!!a;this.B=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.J&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.C=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.A||0<=Za(d.A,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.A=this.i=this.m=null;window.addEventListener("message",this.B)}
v(mo,J);mo.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.C)}catch(d){rg(d)}}};
mo.prototype.D=function(){window.removeEventListener("message",this.B);J.prototype.D.call(this)};function no(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new mo(!!F("WIDGET_ID_ENFORCE")),b=this.Mb.bind(this);a.m=b;a.A=null;this.h.channel="widget";if(a=F("WIDGET_ID"))this.h.sessionId=a}
m=no.prototype;m.Mb=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,oo(this,a)),this.j[a]=!0)):this.Ra(a,b,c)};
m.Ra=function(){};
function oo(a,b){return function(c){return a.sendMessage(b,c)}}
m.addEventListener=function(){};
m.xb=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Ha());this.sendMessage("onReady");E(this.i,this.mb,this);this.i=[]};
m.Ha=function(){return null};
function po(a,b){a.sendMessage("infoDelivery",b)}
m.mb=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.mb({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};function qo(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function ro(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function so(a,b,c,d){if(La(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function to(a){no.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Tb.bind(this));this.addEventListener("onVolumeChange",this.Ub.bind(this));this.addEventListener("onApiChange",this.Ob.bind(this));this.addEventListener("onPlaybackQualityChange",this.Qb.bind(this));this.addEventListener("onPlaybackRateChange",this.Rb.bind(this));this.addEventListener("onStateChange",this.Sb.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Vb.bind(this))}
v(to,no);m=to.prototype;
m.Ra=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&qo(a)){var d=b;if(La(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=ro(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=ro(e);break;case "loadPlaylist":case "cuePlaylist":e=so(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);qo(a)&&po(this,this.Ha())}};
m.onReady=function(){var a=this.xb.bind(this);this.h.i=a};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Ha=function(){if(!this.api)return null;var a=this.api.getApiInterface();db(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Sb=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());po(this,a)};
m.Qb=function(a){po(this,{playbackQuality:a})};
m.Rb=function(a){po(this,{playbackRate:a})};
m.Ob=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Ub=function(){po(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Tb=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());po(this,a)};
m.Vb=function(){var a={sphericalProperties:this.api.getSphericalProperties()};po(this,a)};
m.dispose=function(){no.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function uo(a){J.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.ib,this)}
v(uo,J);m=uo.prototype;m.start=function(){this.started||this.h||(this.started=!0,this.connection.ea("RECEIVING"))};
m.ea=function(a,b){this.started&&!this.h&&this.connection.ea(a,b)};
m.ib=function(a,b,c){if(this.started&&!this.h){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=vo(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=wo(a,c))&&this.ea(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Pb.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Pb=function(a,b){this.started&&!this.h&&this.connection.ea(a,this.Ga(a,b))};
m.Ga=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.D=function(){var a=this.connection;a.h||Pf(a.i,"command",this.ib,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);J.prototype.D.call(this)};function xo(a,b){uo.call(this,b);this.api=a;this.start()}
v(xo,uo);xo.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
xo.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function vo(a,b){switch(a){case "loadVideoById":return a=ro(b),[a];case "cueVideoById":return a=ro(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=so(b),[a];case "cuePlaylist":return a=so(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function wo(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
xo.prototype.Ga=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return uo.prototype.Ga.call(this,a,b)};
xo.prototype.D=function(){uo.prototype.D.call(this);delete this.api};function yo(a){a=void 0===a?!1:a;J.call(this);this.i=new L(a);te(this,Ta(re,this.i))}
D(yo,J);yo.prototype.subscribe=function(a,b,c){return this.h?0:this.i.subscribe(a,b,c)};
yo.prototype.l=function(a,b){this.h||this.i.da.apply(this.i,arguments)};function zo(a,b,c){yo.call(this);this.j=a;this.destination=b;this.id=c}
v(zo,yo);zo.prototype.ea=function(a,b){this.h||this.j.ea(this.destination,this.id,a,b)};
zo.prototype.D=function(){this.destination=this.j=null;yo.prototype.D.call(this)};function Ao(a,b,c){J.call(this);this.destination=a;this.origin=c;this.i=Gg(window,"message",this.j.bind(this));this.connection=new zo(this,a,b);te(this,Ta(re,this.connection))}
v(Ao,J);Ao.prototype.ea=function(a,b,c,d){this.h||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(pf(a),this.origin))};
Ao.prototype.j=function(a){var b;if(b=!this.h)if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h||c.l("command",b.command,b.data,a.origin))}};
Ao.prototype.D=function(){Hg(this.i);this.destination=null;J.prototype.D.call(this)};function Bo(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||nb(b);this.assets=a.assets||{};this.attrs=a.attrs||nb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Bo.prototype.clone=function(){var a=new Bo,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ja(c)?a[b]=nb(c):a[b]=c}return a};var Co=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Do(a){a=a||"";if(window.spf){var b=a.match(Co);spf.style.load(a,b?b[1]:"",void 0)}else Eo(a)}
function Eo(a){var b=Fo(a),c=document.getElementById(b),d=c&&Kn(c,"loaded");d||c&&!d||(c=Go(a,b,function(){Kn(c,"loaded")||(In(c),Rh(b),Jg(Ta(Sh,b),0))}))}
function Go(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=nf(a);ac(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Fo(a){var b=wd(document,"A");vb("This URL is never added to the DOM");$b(b,new Kb(a,Lb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+ec(a)}
;function Ho(){J.call(this);this.i=[]}
v(Ho,J);Ho.prototype.D=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.Ta,void 0)}J.prototype.D.call(this)};function Io(){Ho.apply(this,arguments)}
v(Io,Ho);function Jo(a,b,c,d){J.call(this);var e=this;this.J=b;this.webPlayerContextConfig=d;this.Ca=!1;this.api={};this.ha=this.A=null;this.L=new L;this.i={};this.U=this.na=this.elementId=this.Da=this.config=null;this.T=!1;this.l=this.B=null;this.oa={};this.pb=["onReady"];this.lastError=null;this.Sa=NaN;this.C={};this.qb=new Io(this);this.ga=0;this.j=this.m=a;te(this,Ta(re,this.L));Ko(this);Lo(this);te(this,Ta(re,this.qb));c?this.ga=Jg(function(){e.loadNewVideoConfig(c)},0):d&&(Mo(this),No(this))}
v(Jo,J);m=Jo.prototype;m.getId=function(){return this.J};
m.loadNewVideoConfig=function(a){if(!this.h){this.ga&&(Kg(this.ga),this.ga=0);var b=a||{};b instanceof Bo||(b=new Bo(b));this.config=b;this.setConfig(a);No(this);this.isReady()&&Oo(this)}};
function Mo(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.J,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.J:a.config.attrs.id=a.J);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){var b;this.Da=a;this.config=Po(a);Mo(this);this.na||(this.na=Qo(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=Fd(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=Fd(Number(a)||a))};
function Oo(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function Ro(a){var b=!0,c=So(a);c&&a.config&&(a=To(a),b=Kn(c,"version")===a);return b&&!!C("yt.player.Application.create")}
function No(a){if(!a.h&&!a.T){var b=Ro(a);if(b&&"html5"===(So(a)?"html5":null))a.U="html5",a.isReady()||Uo(a);else if(Vo(a),a.U="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Uo(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.B=function(){c=!0;var d=Wo(a,"player_bootstrap_method")?C("yt.player.Application.createAlternate")||C("yt.player.Application.create"):C("yt.player.Application.create");var e=a.config?Po(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig);Uo(a)};
a.T=!0;b?a.B():(On(To(a),a.B),(b=Xo(a))&&Do(b),Yo(a)&&!c&&A("yt.player.Application.create",null,void 0))}}}
function So(a){var b=sd(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Uo(a){var b;if(!a.h){var c=So(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.T=!1,!Wo(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||Zo(a)):a.Sa=Jg(function(){Uo(a)},50)}}
function Zo(a){Ko(a);a.Ca=!0;var b=So(a);if(b){a.A=$o(a,b,"addEventListener");a.ha=$o(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=$o(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.A&&a.A(g,a.i[g]);Oo(a);a.na&&a.na(a.api);a.L.da("onReady",a.api)}
function $o(a,b,c){var d=b[c];return function(e){for(var f=[],g=0;g<arguments.length;++g)f[g-0]=arguments[g];try{return a.lastError=null,d.apply(b,f)}catch(h){"sendAbandonmentPing"!==c&&(h.params=c,a.lastError=h,Ql(h))}}}
function Ko(a){a.Ca=!1;if(a.ha)for(var b in a.i)a.i.hasOwnProperty(b)&&a.ha(b,a.i[b]);for(var c in a.C)a.C.hasOwnProperty(c)&&Kg(Number(c));a.C={};a.A=null;a.ha=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Da};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ca};
function Lo(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Rh("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Rh("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){Rh("a11y-announce",b)})}
m.addEventListener=function(a,b){var c=this,d=Qo(this,b);d&&(0<=Za(this.pb,a)||this.i[a]||(b=ap(this,a),this.A&&this.A(a,b)),this.L.subscribe(a,d),"onReady"===a&&this.isReady()&&Jg(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h||(b=Qo(this,b))&&Pf(this.L,a,b)};
function Qo(a,b){var c=b;if("string"===typeof b){if(a.oa[b])return a.oa[b];c=function(d){for(var e=[],f=0;f<arguments.length;++f)e[f-0]=arguments[f];if(f=C(b))try{f.apply(z,e)}catch(g){Rl(g)}};
a.oa[b]=c}return c?c:null}
function ap(a,b){var c="ytPlayer"+b+a.J;a.i[b]=c;z[c]=function(d){var e=Jg(function(){if(!a.h){a.L.da(b,d);var f=a.C,g=String(e);g in f&&delete f[g]}},0);
kb(a.C,String(e))};
return c}
m.getPlayerType=function(){return this.U||(So(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function Vo(a){a.cancel();Ko(a);a.U=null;a.config&&(a.config.loaded=!1);var b=So(a);b&&(Ro(a)||!Yo(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.B&&Un(To(this),this.B);Kg(this.Sa);this.T=!1};
m.D=function(){Vo(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Rl(b)}this.oa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(z[this.i[a]]=null);this.Da=this.config=this.api=null;delete this.m;delete this.j;J.prototype.D.call(this)};
function Yo(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function To(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Xo(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Wo(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===ch(d||"","&")[b]}
function Po(a){for(var b={},c=u(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?nb(e):e}return b}
;var bp={},cp="player_uid_"+(1E9*Math.random()>>>0);function dp(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?sd(d):d;var e=cp+"_"+Ma(d),f=bp[e];if(f&&c)return ep(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Jo(d,e,a,b);bp[e]=f;Rh("player-added",f.api);te(f,function(){delete bp[f.getId()]});
return f.api}
function ep(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var fp=null,gp=null,hp=null;function ip(){var a=fp.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function jp(a,b,c){a="ST-"+ec(a).toString(36);b=b?jc(b):"";c=c||5;am()&&ri(a,b,c)}
;function kp(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=F("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=F("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=hc(window.location.href);g&&f.push(g);g=hc(d);if(0<=Za(f,g)||!g&&0==d.lastIndexOf("/",0))if(N("autoescape_tempdata_url")&&(f=document.createElement("a"),$b(f,d),d=f.href),d){g=d.match(fc);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:vm()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&jp(d,b,k)}else jp(d,b)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var n=void 0===n?"":n;var p=void 0===p?window:p;c=p.location;a=kc(a,l)+n;var r=void 0===r?nd:r;a:{r=void 0===r?nd:r;for(l=0;l<r.length;++l)if(n=r[l],n instanceof ld&&n.isValid(a)){r=new jd(a,hd);break a}r=void 0}c.href=od(r||kd)}return!0}
;A("yt.setConfig",M,void 0);A("yt.config.set",M,void 0);A("yt.setMsg",tg,void 0);A("yt.msgs.set",tg,void 0);A("yt.logging.errors.log",Rl,void 0);
A("writeEmbed",function(){var a=F("PLAYER_CONFIG",void 0);if(!a){var b=F("PLAYER_VARS",void 0);b&&(a={args:b})}im(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=F("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);N("embeds_js_api_set_1p_cookie")&&(c=hh(),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));M("FORCE_CSI_ON_GEL",!0);
c=["ol"];en("").info.actionType="embed";c&&M("TIMING_AFT_KEYS",c);M("TIMING_ACTION","embed");c=F("TIMING_INFO",{});for(var d in c)c.hasOwnProperty(d)&&wn(d,c[d]);wn("is_nav",1);(d=vm())&&wn("csn",d);(d=F("PREVIOUS_ACTION",void 0))&&!rn()&&wn("pa",d);d=$m();c=F("CLIENT_PROTOCOL");var e=F("CLIENT_TRANSPORT");c&&wn("p",c);e&&wn("t",e);wn("yt_vis",zn());wn("yt_lt","cold");c=Wm();if(e=Ym())Z("srt",c.responseStart),1!==d.prerender&&(wn("yt_sts","n",void 0),Z("_start",e,void 0));d=cn();0<d&&Z("fpt",d);d=
Wm();d.isPerformanceNavigationTiming&&wn("pnt",1,void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Ym()&&0<d.connectEnd-
d.secureConnectionStart&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));W&&W.getEntriesByType&&Bn();d=[];if(document.querySelector&&W&&W.getEntriesByName)for(var f in Tm)Tm.hasOwnProperty(f)&&(c=Tm[f],An(f,c)&&d.push(c));for(f=0;f<d.length;f++)wn("rc",d[f]);if(rn(void 0)){f={actionType:ln[F("TIMING_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN",previousAction:ln[F("PREVIOUS_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN"};if(d=vm())f.clientScreenNonce=d;d=an(void 0);c=Zm(void 0).cttAuthInfo;
jn().info(f,d,c)}f=$m();c=Vm();if("cold"===f.yt_lt&&(d=tn(),e=d.gelTicks?d.gelTicks:d.gelTicks={},d=d.gelInfos?d.gelInfos:d.gelInfos={},rn())){for(var g in c)"tick_"+g in e||sn(g,c[g]);g=vn();c=an();e=Zm().cttAuthInfo;var h={},k=!1,l;for(l in f)if(!("info_"+l in d)){var n=un(l,f[l]);n&&(Hm(g,n),Hm(h,n),k=!0)}k&&jn().info(h,c,e)}A("ytglobal.timingready_",!0,void 0);xn();(l=F("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in l?(l=l.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,
l.serializedForcedExperimentIds||(g=hh(),g.forced_experiments&&(l.serializedForcedExperimentIds=g.forced_experiments)),fp=dp(a,l,!1)):fp=dp(a);fp.addEventListener("onVideoDataChange",ip);a=F("POST_MESSAGE_ID","player");F("ENABLE_JS_API")?hp=new to(fp):F("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(gp=new Ao(window.parent,a,b),hp=new xo(fp,gp.connection));Xn();N("networkless_logging_web_embedded")&&(N("embeds_web_enable_new_nwl")?wl():el());N("embeds_enable_ua_ch_polyfill")&&lo()},
void 0);
var lp=pg(function(){yn();var a=ti.getInstance(),b=!!((wi("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&we(document.body,"exp-invert-logo"))if(c&&!we(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!we(d,"inverted-hdpi")){var e=ue(d);ve(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&we(document.body,"inverted-hdpi")&&xe();if(b!=c){b="f"+(Math.floor(119/31)+1);d=wi(b)||0;d=c?d|67108864:
d&-67108865;0==d?delete si[b]:(c=d.toString(16),si[b]=c.toString());c=!0;N("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in si)d.push(f+"="+encodeURIComponent(String(si[f])));ri(b,d.join("&"),63072E3,a.i,c)}Dn.h||(Dn.h=new Dn);a=Dn.h;f=16623;var g=void 0===g?{}:g;Object.values(Tl).includes(f)||(Ql(new Pi("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.o=[];a.A=[];g.Xa?Gn(a,f,g):Hn(a,f,g)}),mp=pg(function(){fp&&
fp.sendAbandonmentPing&&fp.sendAbandonmentPing();
F("PL_ATT")&&co.dispose();for(var a=0,b=Vn.length;a<b;a++)Sg(Vn[a]);Vn.length=0;Tn("//static.doubleclick.net/instream/ad_status.js");Wn=!1;M("DCLKSTAT",0);se(hp,gp);fp&&(fp.removeEventListener("onVideoDataChange",ip),fp.destroy())});
window.addEventListener?(window.addEventListener("load",lp),window.addEventListener("unload",mp)):window.attachEvent&&(window.attachEvent("onload",lp),window.attachEvent("onunload",mp));Ua("yt.abuse.player.botguardInitialized",C("yt.abuse.player.botguardInitialized")||eo);Ua("yt.abuse.player.invokeBotguard",C("yt.abuse.player.invokeBotguard")||fo);Ua("yt.abuse.dclkstatus.checkDclkStatus",C("yt.abuse.dclkstatus.checkDclkStatus")||Yn);
Ua("yt.player.exports.navigate",C("yt.player.exports.navigate")||kp);Ua("yt.util.activity.init",C("yt.util.activity.init")||Ug);Ua("yt.util.activity.getTimeSinceActive",C("yt.util.activity.getTimeSinceActive")||Xg);Ua("yt.util.activity.setTimestamp",C("yt.util.activity.setTimestamp")||Vg);}).call(this);
