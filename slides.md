![ASDI](https://i.ytimg.com/vi/c4Nd8ydxVpI/maxresdefault.jpg)
---
## Improving The ASDI Experience

---
ASDI's organic, decentralized approach has worked great in several aspects.

- Minimal gatekeeping lowers the barrier of entry for data providers.<!-- .element: class="fragment" -->
- Gives large federal data providers like NOAA a space for experimentation.<!-- .element: class="fragment" -->
- As intended, it has truly democratized access to planetary scale data.<!-- .element: class="fragment" -->

---
But the same aspects that make it successful also reduce its effectiveness

- Limited centralized oversight leads to a lack of focus on important thematic areas.<!-- .element: class="fragment" -->
- Lack of standardization reduces data interoperability for data users.<!-- .element: class="fragment" -->
- The lack of a centralized indexing and search inteface makes data discovery and fusion impossible for data users.<!-- .element: class="fragment" -->

---
### How can we improve the ASDI experience for the data community?
---
### Step 1
Adopt a common metadata standard.
---
![STAC](https://raw.githubusercontent.com/radiantearth/stac-site/master/images/logo/stac-030-long.png)
---
STAC is a community driven standard for metadata and metadata APIs.

Rather than originitating with a standards body like OGC, STAC evolved from industry and community members who had immediate, common problems to solve.
---
![STAC history](https://staging.dev.element84.com/wp-content/uploads/2023/03/STAC_timeline_v2.jpg)

---
<!-- .slide: data-background-color="white" -->
![Development Seed](http://summit2015.hotosm.org/img/sponsor_logos/silver_devseed.png)
---
Development Seed has been involved with STAC since its inception.

We've built both the main reference implementations of the API standard as well as suite of tooling for working with the metadata specification.
---
<!-- .slide: data-background-color="white" -->
Most relevant to this project is our work building the API infrastructure for Microsoft's Planetary Computer
![Planetary Computer](https://staging.dev.element84.com/wp-content/uploads/2023/05/Screenshot-2023-05-01-at-5.13.58-PM-1024x255.png)
---
The Planetary Computer obviously runs on Azure.
But the bulk of the NASA projects we build use the same suite of libraries deployed on AWS.
---
<!-- .slide: data-background-color="white" -->
![VEDA](https://www.earthdata.nasa.gov/s3fs-public/styles/small_third_320px_/public/2022-08/veda_logo_landing.jpg?VersionId=WSeWbp1l67IFvS2xOSXB2AdHF_78VzQX&itok=NEqHRpxW)
![MAAP](https://www.earthdata.nasa.gov/s3fs-public/styles/medium_half_480px_/public/2022-02/MAAP_logo.jpg?VersionId=zowUUuoD1OfbXTyTWlc_KLs6TnU1DNI6&itok=kEbXx7uI)
![CSDA](https://www.earthdata.nasa.gov/s3fs-public/2023-01/csda-logo-150x150.png?VersionId=f7cRgCo9oXtjHTCkCrxmS9aiUO16D0pU)
---

NOTE: Could be relative path to images as well...


A quick example set of slides

---

Checkout `slides.md` to see how they were written.

---

## Navigate vertically

Grouping tabs vertically is a good way to discuss a single idea

_hint: press <kbd>↓</kdb>_<!-- .element: class="small" -->

--

This slide appears below the first slide

_hint: press <kbd>→</kdb>_<!-- .element: class="small" -->

---

## Navigate horizontally

This slide appears to the right of the first slide

---

Go Big<!-- .element: class="r-fit-text" -->

---

Press <kbd>ESC</kbd> to see overview

--

Press <kbd>S</kbd> to open speaker view.

You can even include notes that only the presenter can see!

<!-- Presenter notes are specified by anything written below a line that starts with "NOTE: " -->

NOTE: This is only visible to the presenter.

Drag this tab to a different window or screenshare the other tab. When you change slides on this presenter-view tab, the other tab with audience focused tabs will change as well.

--

Press <kbd>?</kbd> to see other keyboard shortcuts.

---

## Fragment transitions

Fade in <!-- .element: class="fragment" -->

Fade out <!-- .element: class="fragment fade-out" -->

Highlight red <!-- .element: class="fragment highlight-red" -->

Fade in, then out <!-- .element: class="fragment fade-in-then-out" -->

Slide up while fading in <!-- .element: class="fragment fade-up" -->

NOTE: See more about fragment transitions here: https://revealjs.com/fragments/

---

<!-- .slide: data-auto-animate -->

## Code

```js[|4|4,8-9|15,19-20]
import React, { useState } from "react";

function Example() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  );
}

function SecondExample() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  );
}
```

---


<!-- .slide: data-background-image="https://placekitten.com/1000/1000" -->

## Backgrounds

Images as backgrounds

NOTE: Could be relative path to images as well...

--

<!-- .slide: data-background-iframe="https://semver.org" data-background-interactive -->

## Backgrounds

Websites as backgrounds

NOTE: This doesn't currently work with any page that prevents itself from being included in iframes (e.g. GitHub)
