---
title: Button
---

## Basic

{{< code html >}}
<a href="#" class="btn btn-primary" role="button">Link</a>
<button class="btn btn-primary">Button</button>
<input type="button" class="btn btn-primary" value="Input" />
<input type="submit" class="btn btn-primary" value="Submit" />
<input type="reset" class="btn btn-primary" value="Reset" />
{{< /code >}}

## Colors

{{< code html >}}
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-success">Success</button>
<button class="btn btn-danger">Danger</button>
<button class="btn btn-warning">Warning</button>
<button class="btn btn-light">Light</button>
<button class="btn btn-dark">Dark</button>
<button class="btn btn-white">White</button>
<button class="btn btn-link">Link</button>
<button class="btn bg-teal-700 hover:bg-teal-900 text-white">Tailwind Color</button>
{{< /code >}}

## Light Colors

{{< code html >}}
<button class="btn btn-light-primary">Primary</button>
<button class="btn btn-light-secondary">Secondary</button>
<button class="btn btn-light-success">Success</button>
<button class="btn btn-light-danger">Danger</button>
<button class="btn btn-light-warning">Warning</button>
<button class="btn btn-light-link">Link</button>
{{< /code >}}

## Outline

{{< code html >}}
<button class="btn btn-outline-primary">Button</button>
<button class="btn btn-outline-secondary">Button</button>
<button class="btn btn-outline-success">Button</button>
<button class="btn btn-outline-danger">Button</button>
<button class="btn btn-outline-warning">Button</button>
<button class="btn btn-outline-light">Button</button>
<button class="btn btn-outline-dark">Button</button>
<button class="btn btn-outline-link">Button</button>
{{< /code >}}

## Size

{{< code html >}}
<button class="btn btn-primary btn-xs">Extra Small</button>
<button class="btn btn-primary btn-sm">Small</button>
<button class="btn btn-primary">Normal</button>
<button class="btn btn-primary btn-lg">Large</button>
<button class="btn btn-primary btn-xl">Extra Large</button>
{{< /code >}}

## Block

{{< code html >}}
<button class="btn btn-primary w-full">Button</button>
{{< /code >}}

## Pill

{{< code html >}}
<button class="btn btn-primary rounded-full">Button</button>
<button class="btn btn-secondary rounded-full">Button</button>
<button class="btn btn-success rounded-full">Button</button>
<button class="btn btn-danger rounded-full">Button</button>
<button class="btn btn-warning rounded-full">Button</button>
<button class="btn btn-light rounded-full">Button</button>
<button class="btn btn-dark rounded-full">Button</button>
<button class="btn btn-link rounded-full">Button</button>
{{< /code >}}

## Square

{{< code html >}}
<button class="btn btn-primary rounded-none">Button</button>
<button class="btn btn-secondary rounded-none">Button</button>
<button class="btn btn-success rounded-none">Button</button>
<button class="btn btn-danger rounded-none">Button</button>
<button class="btn btn-warning rounded-none">Button</button>
<button class="btn btn-light rounded-none">Button</button>
<button class="btn btn-dark rounded-none">Button</button>
<button class="btn btn-link rounded-none">Button</button>
{{< /code >}}

## Button Group

{{< code html >}}

<div class="space-x-1">
  <div class="btn-group" role="group" aria-label="Align Text">
    <button type="button" class="btn btn-light">Left</button>
    <button type="button" class="btn btn-light">Center</button>
    <button type="button" class="btn btn-light">Right</button>
  </div>
  <div class="btn-group" role="group" aria-label="Align Text">
    <button type="button" class="btn btn-light btn-icon"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="17" y1="10" x2="3" y2="10"></line><line x1="21" y1="6" x2="3" y2="6"></line><line x1="21" y1="14" x2="3" y2="14"></line><line x1="17" y1="18" x2="3" y2="18"></line></svg><span class="sr-only">Left</span></button>
    <button type="button" class="btn btn-light btn-icon"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="10" x2="6" y2="10"></line><line x1="21" y1="6" x2="3" y2="6"></line><line x1="21" y1="14" x2="3" y2="14"></line><line x1="18" y1="18" x2="6" y2="18"></line></svg><span class="sr-only">Center</span></button>
    <button type="button" class="btn btn-light btn-icon"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="21" y1="10" x2="7" y2="10"></line><line x1="21" y1="6" x2="3" y2="6"></line><line x1="21" y1="14" x2="3" y2="14"></line><line x1="21" y1="18" x2="7" y2="18"></line></svg><span class="sr-only">Right</span></button>
  </div>
</div>
{{< /code >}}

## Disabled

{{< code html >}}
<button class="btn btn-primary" disabled>Button</button>
<button class="btn btn-secondary" disabled>Button</button>
<button class="btn btn-success" disabled>Button</button>
<button class="btn btn-danger" disabled>Button</button>
<button class="btn btn-warning" disabled>Button</button>
<button class="btn btn-light" disabled>Button</button>
<button class="btn btn-dark" disabled>Button</button>
<button class="btn btn-link" disabled>Button</button>
{{< /code >}}

## Loading

{{< code html >}}
<button class="btn btn-primary btn-loading">
<span class="spinner w-4 h-4" role="status" aria-hidden="true"></span>
<span class="sr-only">Loading...</span>
</button>
<button class="btn btn-outline-dark btn-loading">
<span class="spinner w-4 h-4" role="status" aria-hidden="true"></span>
<span class="pl-2">Loading...</span>
</button>
<button class="btn btn-success btn-sm btn-loading">
<span class="spinner w-4 h-4" role="status" aria-hidden="true"></span>
<span class="sr-only">Loading...</span>
</button>
<button class="btn btn-light btn-lg btn-loading">
<span class="spinner w-4 h-4" role="status" aria-hidden="true"></span>
<span class="sr-only">Loading...</span>
</button>
{{< /code >}}

## Icons Button

{{< code html >}}
<button class="btn btn-icon btn-primary">
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="7 10 12 15 17 10"></polyline><line x1="12" y1="15" x2="12" y2="3"></line></svg>
<span class="sr-only">Button</span>
</button>
<button class="btn btn-icon btn-outline-danger"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path></svg><span class="sr-only">Button</span></button>
<button class="btn btn-icon btn-sm btn-success"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect><path d="M7 11V7a5 5 0 0 1 10 0v4"></path></svg><span class="sr-only">Button</span></button>
<button class="btn btn-icon btn-lg btn-light"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="22 12 16 12 14 15 10 15 8 12 2 12"></polyline><path d="M5.45 5.11L2 12v6a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-6l-3.45-6.89A2 2 0 0 0 16.76 4H7.24a2 2 0 0 0-1.79 1.11z"></path></svg><span class="sr-only">Button</span></button>
<button class="btn btn-icon rounded-full btn-dark"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path></svg><span class="sr-only">Button</span></button>
<button class="btn btn-icon rounded-none btn-outline-light"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="8" y1="15" x2="16" y2="15"></line><line x1="9" y1="9" x2="9.01" y2="9"></line><line x1="15" y1="9" x2="15.01" y2="9"></line></svg><span class="sr-only">Button</span></button>
{{< /code >}}

## Button with Icon

{{< code html >}}
<button class="btn btn-icon btn-primary"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-1"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="7 10 12 15 17 10"></polyline><line x1="12" y1="15" x2="12" y2="3"></line></svg>Button</button>
<button class="btn btn-icon btn-outline-danger"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-1"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path></svg>Button</button>
<button class="btn btn-icon btn-sm btn-success"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-1"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect><path d="M7 11V7a5 5 0 0 1 10 0v4"></path></svg>Button</button>
<button class="btn btn-icon btn-lg btn-light"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-1"><polyline points="22 12 16 12 14 15 10 15 8 12 2 12"></polyline><path d="M5.45 5.11L2 12v6a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-6l-3.45-6.89A2 2 0 0 0 16.76 4H7.24a2 2 0 0 0-1.79 1.11z"></path></svg>Button</button>
<button class="btn btn-icon rounded-full btn-dark"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-1"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path></svg>Button</button>
<button class="btn btn-icon rounded-none btn-outline-light"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-1"><circle cx="12" cy="12" r="10"></circle><line x1="8" y1="15" x2="16" y2="15"></line><line x1="9" y1="9" x2="9.01" y2="9"></line><line x1="15" y1="9" x2="15.01" y2="9"></line></svg>Button</button>
{{< /code >}}

## List

{{< code html >}}

<div class="btn-list">
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
  <button class="btn btn-light">Button</button>
</div>

{{< /code >}}

## Social

{{< code html >}}

<button class="btn btn-twitter">Twitter</button>
<button class="btn btn-youtube">YouTube</button>
<button class="btn btn-instagram">Instagram</button>
<button class="btn btn-github">GitHub</button>
<button class="btn btn-google">Google</button>
<button class="btn btn-twitch">Twitch</button>
<button class="btn btn-linkedin">LinkedIn</button>
<button class="btn btn-slack">Slack</button>
<button class="btn btn-facebook">Facebook</button>

{{< /code >}}

## Social Icons

{{< code html >}}

<button class="btn btn-icon btn-twitter"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"></path></svg></button>
<button class="btn btn-icon btn-youtube"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"></path><polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon></svg></button>
<button class="btn btn-icon btn-instagram"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg></button>
<button class="btn btn-icon btn-github"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg></button>
<button class="btn btn-icon btn-google"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.283,10.356h-8.327v3.451h4.792c-0.446,2.193-2.313,3.453-4.792,3.453c-2.923,0-5.279-2.356-5.279-5.28	c0-2.923,2.356-5.279,5.279-5.279c1.259,0,2.397,0.447,3.29,1.178l2.6-2.599c-1.584-1.381-3.615-2.233-5.89-2.233	c-4.954,0-8.934,3.979-8.934,8.934c0,4.955,3.979,8.934,8.934,8.934c4.467,0,8.529-3.249,8.529-8.934	C20.485,11.453,20.404,10.884,20.283,10.356z"/></svg></button>
<button class="btn btn-icon btn-twitch"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 2H3v16h5v4l4-4h5l4-4V2zm-10 9V7m5 4V7"></path></svg></button>
<button class="btn btn-icon btn-linkedin"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg></button>
<button class="btn btn-icon btn-slack"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 10c-.83 0-1.5-.67-1.5-1.5v-5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v5c0 .83-.67 1.5-1.5 1.5z"></path><path d="M20.5 10H19V8.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5-.67 1.5-1.5 1.5z"></path><path d="M9.5 14c.83 0 1.5.67 1.5 1.5v5c0 .83-.67 1.5-1.5 1.5S8 21.33 8 20.5v-5c0-.83.67-1.5 1.5-1.5z"></path><path d="M3.5 14H5v1.5c0 .83-.67 1.5-1.5 1.5S2 16.33 2 15.5 2.67 14 3.5 14z"></path><path d="M14 14.5c0-.83.67-1.5 1.5-1.5h5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5h-5c-.83 0-1.5-.67-1.5-1.5z"></path><path d="M15.5 19H14v1.5c0 .83.67 1.5 1.5 1.5s1.5-.67 1.5-1.5-.67-1.5-1.5-1.5z"></path><path d="M10 9.5C10 8.67 9.33 8 8.5 8h-5C2.67 8 2 8.67 2 9.5S2.67 11 3.5 11h5c.83 0 1.5-.67 1.5-1.5z"></path><path d="M8.5 5H10V3.5C10 2.67 9.33 2 8.5 2S7 2.67 7 3.5 7.67 5 8.5 5z"></path></svg></button>
<button class="btn btn-icon btn-facebook"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg></button>

{{< /code >}}
