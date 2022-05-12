---
layout: post
title:  "This is my first post!"
date:   2022-05-12 16:12:18 +0900
categories: test
---

I wish post own my blog for my stories!

{% highlight csharp %}
if(this.published)
    available();
{% endhighlight %}

한글 테스트

처음으로 블로그를 만들었다, 이것은 나의 기록을 남기는데 유용하게 사용될 전망이다.

{% highlight java %}
package com.example.demo;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestParam;

@SpringBootApplication
public class DemoApplication {

	public static void main(String[] args) {
		SpringApplication.run(DemoApplication.class, args);
	}
	
	@GetMapping("/hello")
	public String hello(@RequestParam(value = "name", defaultValue = "World") String name) {
		return String.format("Hello %s!", name);
	}
{% endhighlight %}