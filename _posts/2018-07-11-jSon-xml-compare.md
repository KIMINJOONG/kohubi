---
layout: post
title: JSON 과 XML을 비교해보자!
date:   2018-07-11
excerpt: "JSON과 XML의 공통점과 차이점"
image: ""
---
<div class="row">
  <h2>XML이란?</h2>
  <p style="width :100%">
  XML은 EXtensible Markup Language의 약자입니다.

이러한 XML은 HTML과 매우 비슷한 문자 기반의 마크업 언어(text-based markup language)입니다.

이 언어는 사람과 기계가 동시에 읽기 편한 구조로 되어 있습니다.

 

XML은 HTML처럼 데이터를 보여주는 목적이 아닌, 데이터를 저장하고 전달할 목적으로만 만들어졌습니다.

또한, XML 태그는 HTML 태그처럼 미리 정의되어 있지 않고, 사용자가 직접 정의할 수 있습니다.
</p>

  <h2 style="width :100%">JSON과 XML의 공통점</h2>
  <h4 style="width :100%">JSON과 XML은 다음과 같은 공통점을 가지고 있습니다.</h4>
  <ol style="width :100%">
    <li>둘 다 데이터를 저장하고 전달하기 위해 고안되었습니다.</li>
    <li>둘 다 기계뿐만 아니라 사람도 쉽게 읽을 수 있습니다.</li>
    <li>둘 다 계층적인 데이터 구조를 가집니다.</li>
    <li>둘 다 다양한 프로그래밍 언어에 의해 파싱될 수 있습니다.</li>
    <li>둘 다 XMLHttpRequest 객체를 이용하여 서버로부터 데이터를 전송받을 수 있습니다.</li>
  </ol>
  
  <h2 style="width :100%">JSON과 XML의 차이점</h2>
  <h4 style="width :100%">하지만 JSON과 XML은 다음과 같은 차이점도 가지고 있습니다.</h4>
  <ol style="width :100%">
    <li>JSON은 종료 태그를 사용하지 않습니다.</li>
    <li>JSON의 구문이 XML의 구문보다 더 짧습니다.</li>
    <li>JSON 데이터가 XML 데이터보다 더 빨리 읽고 쓸 수 있습니다.</li>
    <li>XML은 배열을 사용할 수 없지만, JSON은 배열을 사용할 수 있습니다.</li>
    <li> XML은 XML 파서로 파싱되며, JSON은 자바스크립트 표준 함수인 eval() 함수로 파싱됩니다.</li>
  </ol>
  
  <h2 style="width :100%">XML 예제</h2>
  <pre style="width :100%">
  <code>
  &lt;dog&gt;
    &lt;name&gt;식빵&lt;/name&gt;
    &lt;family&gt;웰시코기&lt;family&gt;
    &lt;age&gt;1&lt;/age&gt;
    &lt;weight&gt;2.14&lt;/weight&gt;
  &lt;/dog&gt;
  </code>
  </pre>
  
 <h2 style="width :100%">JSON 예제</h2>
 <pre style="width :100%">
 <code>
 {
    "name": "식빵",
    "family": "웰시코기",
    "age": 1,
    "weight": 2.14
}
 </code>
 </pre>
 <h2>JSON</h2>
 <p style="width :100%">
 XML 문서는 XML DOM(Document Object Model)을 이용하여 해당 문서에 접근합니다.

하지만 JSON은 문자열을 전송받은 후에 해당 문자열을 바로 파싱하므로, XML보다 더욱 빠른 처리 속도를 보여줍니다.

따라서 HTML과 자바스크립트가 연동되어 빠른 응답이 필요한 웹 환경에서 많이 사용되고 있습니다.

 

하지만 JSON은 전송받은 데이터의 무결성을 사용자가 직접 검증해야 합니다.

따라서 데이터의 검증이 필요한 곳에서는 스키마를 사용하여 데이터의 무결성을 검증할 수 있는 XML이 아직도 많이 사용되고 있습니다.
 </p>
 <p>
  <a href="http://ooz.co.kr/199">http://ooz.co.kr/199 참조</a>
  </p>
</div>
