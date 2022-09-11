# Becoming Agile

![replace_me](https://codeworks.blob.core.windows.net/public/assets/img/illustrations/placeholder.svg)

> When in doubt Scrum it out.

> **📖 [Base64 Images](https://codeworksacademy.com/fs-student-guide/resources/wk8-9/06-Base64)**

## Questions

1. What is a Base64 Encoded Image?

 Base64 is a way of using an already open HTTP connection to deliver images embedded directly into the HTML or CSS.

2. What are the drawbacks of using Base64 Encoding?

The drawbacks of Base64 is that it increases the download size, overhead on the CPU, and perhaps the biggest performance killer, but perhaps not the most obvious at first glance, caching issues.

3. Why are these drawbacks issues in this day and age versus in the past?

Back then, web browsers had heavy limits on the number of concurrent connections they could send to the server. This meant an image heavy website would need to queue up requests and wait for the ones before to finish. Base64 provided a way of working around that by using an already open HTTP connection to deliver images embedded directly into the HTML or CSS. This effectively removed the need for an extra roundtrip the browser would need for each of the files.

## Afternoon Assignment Link

**[Repo](https://github.com/fullmer24/<ASSIGNMENT_REPO>)**

Identify at least 1 takeaway from today's work
