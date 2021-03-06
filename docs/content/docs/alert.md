---
title: Alert
---

## Basic

{{< code html >}}

<div class="space-y-2">
  <div class="alert bg-primary-light text-primary" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-primary-light text-primary alert-closable" role="alert" x-data="{ open: true }" x-show.transition="open">
    I'm a alert that informs you of stuff
    <button class="btn btn-light-primary btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
</div>
{{< /code >}}

## Colors

{{< code html >}}

<div class="space-y-2">
  <div class="alert bg-primary-light text-primary" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-primary text-white" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-green-200 text-green-800" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-green-700 text-white" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-red-200 text-red-700" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-red-700 text-white" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-yellow-200 text-yellow-800" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-yellow-600 text-white" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-gray-200 text-gray-900" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-gray-900 text-white" role="alert">I'm a alert that informs you of stuff</div>
</div>
{{< /code >}}

## Outline

{{< code html >}}

<div class="space-y-2">
  <div class="alert border text-primary" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert border text-green-700" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert border text-red-700" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert border text-yellow-700" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert border text-gray-200" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert border text-gray-900" role="alert">I'm a alert that informs you of stuff</div>
</div>
{{< /code >}}

## Bordered

{{< code html >}}

<div class="space-y-2">
  <div class="alert bg-primary-light text-primary border-t-4 rounded-none" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-green-200 text-green-800 border-l-4 rounded-none" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-red-200 text-red-700 border-r-4 rounded-none" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-yellow-200 text-yellow-800 border-b-4 rounded-none" role="alert">I'm a alert that informs you of stuff</div>
</div>
{{< /code >}}

## Size

{{< code html >}}

<div class="space-y-2">
  <div class="alert bg-primary-light text-primary alert-sm" role="alert">I'm a small alert for less important stuff.</div>
  <div class="alert bg-primary-light text-primary" role="alert">I'm a alert that informs you of stuff</div>
  <div class="alert bg-primary-light text-primary alert-lg" role="alert">I'm a big boy alert that is very important.</div>
</div>
{{< /code >}}

## Status

{{< code html >}}

<div class="space-y-2">
  <div class="alert bg-primary-light text-primary" role="alert"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="16" x2="12" y2="12"></line><line x1="12" y1="8" x2="12.01" y2="8"></line></svg> I'm a alert that informs you of stuff</div>
  <div class="alert bg-green-200 text-green-800" role="alert"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg> I'm a alert that informs you of stuff</div>
  <div class="alert bg-red-200 text-red-700" role="alert"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="4.93" y1="4.93" x2="19.07" y2="19.07"></line></svg> I'm a alert that informs you of stuff</div>
  <div class="alert bg-yellow-200 text-yellow-800" role="alert"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"></path><line x1="12" y1="9" x2="12" y2="13"></line><line x1="12" y1="17" x2="12.01" y2="17"></line></svg> I'm a alert that informs you of stuff</div>
</div>
{{< /code >}}

## With Description

{{< code html >}}

<div class="alert bg-primary-light text-primary" role="alert">
  <div>
    I'm a alert that informs you of stuff
    <span class="flex">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </span>
  </div>
</div>
{{< /code >}}

## Closable

{{< code html >}}

<div class="space-y-2">
  <div class="alert bg-primary-light text-primary alert-closable" role="alert" x-data="{ open: true }" x-show.transition="open">I'm a alert that informs you of stuff
    <button class="btn btn-light-primary btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert bg-primary-light text-primary alert-closable border-t-4 rounded-none" role="alert" x-data="{ open: true }" x-show.transition="open">I'm a alert that informs you of stuff
    <button class="btn btn-light-primary btn-sm rounded-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert bg-primary-light text-primary alert-closable" role="alert" x-data="{ open: true }" x-show.transition="open"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="16" x2="12" y2="12"></line><line x1="12" y1="8" x2="12.01" y2="8"></line></svg> I'm a alert that informs you of stuff
    <button class="btn btn-light-primary btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert border text-primary alert-closable" role="alert" x-data="{ open: true }" x-show.transition="open">I'm a alert that informs you of stuff
    <button class="btn btn-link btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert bg-primary text-white alert-closable" role="alert" x-data="{ open: true }" x-show.transition="open">I'm a alert that informs you of stuff
    <button class="btn btn-primary btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert bg-primary-light text-primary alert-closable alert-sm" role="alert" x-data="{ open: true }" x-show.transition="open">I'm a alert that informs you of stuff
    <button class="btn btn-light-primary btn-xs rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert bg-primary-light text-primary alert-closable alert-lg" role="alert" x-data="{ open: true }" x-show.transition="open">I'm a alert that informs you of stuff
    <button class="btn btn-light-primary btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
  <div class="alert bg-primary-light text-primary alert-closable" role="alert" x-data="{ open: true }" x-show.transition="open">
    <div>
      I'm a alert that informs you of stuff
      <span class="flex">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </span>
    </div>
    <button class="btn btn-light-primary btn-sm rounded-l-none alert-close" @click="open = false"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></button>
  </div>
</div>
{{< /code >}}
