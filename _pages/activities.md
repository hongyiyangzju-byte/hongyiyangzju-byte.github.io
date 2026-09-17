---
permalink: /activities/
title: "Social Activities & Volunteering"
layout: single
author_profile: true
toc: true
---

<!-- NOTE: raw HTML below is indented one space per level on purpose. Four or
     more leading spaces would make kramdown read it as a code block and print
     the tags verbatim. -->

<div class="activity-stats">
 <div class="activity-stat">
  <p class="activity-stat__label">Hours taught as a volunteer</p>
  <p class="activity-stat__value">200+</p>
 </div>
 <div class="activity-stat">
  <p class="activity-stat__label">Long jump, ZJU sports meeting</p>
  <p class="activity-stat__value">3rd</p>
 </div>
 <div class="activity-stat">
  <p class="activity-stat__label">Triple jump, ZJU sports meeting</p>
  <p class="activity-stat__value">5th</p>
 </div>
</div>

## Timeline

<div class="research-timeline">

<article class="research-entry">
 <div class="research-entry__meta">
  <div class="research-entry__logos"></div>
  <div class="research-entry__period">2023 - 2025</div>
 </div>
 <div class="research-entry__content">
  <h3>Track and Field &middot; University Sports Meeting</h3>
  <p class="research-entry__institution">Zhejiang University</p>
  <p>Third place in the long jump and fifth in the triple jump across the 2023 to 2025 meetings, alongside regular track and field training.</p>
 </div>
</article>

<article class="research-entry">
 <div class="research-entry__meta">
  <div class="research-entry__logos"></div>
  <div class="research-entry__period"></div>
 </div>
 <div class="research-entry__content">
  <h3>Volunteer Head Teacher and Physics Tutor</h3>
  <p class="research-entry__institution">Yumin, Xinjiang</p>
  <p>Over 200 hours as a head teacher and physics tutor, and ran science fairs built to get local students interested in physics.</p>
 </div>
</article>

</div>

## Teaching Videos

<div class="video-grid">

<article class="video-card">
 <button class="video-card__poster" type="button" data-bvid="BV13Uj4zpEEF" aria-label="Play lecture 3, relativity">
  <img src="/images/video-lec3-relativity.jpg" alt="" loading="lazy" />
 </button>
 <div class="video-card__body">
  <p class="video-card__title">General Physics, lecture 3: relativity</p>
  <p class="video-card__meta">2024-2025 tutoring programme &middot; <a href="https://www.bilibili.com/video/BV13Uj4zpEEF" rel="noopener">watch on Bilibili</a></p>
 </div>
</article>

<article class="video-card">
 <button class="video-card__poster" type="button" data-bvid="BV1ND421p7hB" aria-label="Play lecture 1, preliminaries, momentum and rotation">
  <img src="/images/video-lec1-mechanics.jpg" alt="" loading="lazy" />
 </button>
 <div class="video-card__body">
  <p class="video-card__title">General Physics, lecture 1: preliminaries, momentum and rotation</p>
  <p class="video-card__meta">2023-2024 tutoring programme &middot; <a href="https://www.bilibili.com/video/BV1ND421p7hB" rel="noopener">watch on Bilibili</a></p>
 </div>
</article>

</div>

## Photos

<div class="photo-gallery">
 <button class="photo-gallery__item" type="button" data-caption="Lessons in Yumin: physics, English vocabulary, and games between classes">
  <img src="/images/activities/teaching.jpg" alt="Teaching a class in Yumin, and playing games with students outside" loading="lazy" />
 </button>
 <button class="photo-gallery__item" type="button" data-caption="Students with their certificates, ink paintings and drawings">
  <img src="/images/activities/student-work.jpg" alt="Students holding certificates and the ink paintings they made" loading="lazy" />
 </button>
 <button class="photo-gallery__item" type="button" data-caption="Closing ceremony and the class group photo">
  <img src="/images/activities/closing-ceremony.jpg" alt="Group photographs at the closing ceremony and in the classroom" loading="lazy" />
 </button>
 <button class="photo-gallery__item" type="button" data-caption="The volunteer team in Yumin, Xinjiang">
  <img src="/images/activities/team-xinjiang.jpg" alt="The volunteer teaching team on the grassland in Yumin" loading="lazy" />
 </button>
</div>

<div class="lightbox" id="lightbox" role="dialog" aria-modal="true" aria-label="Enlarged photo">
 <button class="lightbox__close" type="button" aria-label="Close">&times;</button>
 <img alt="" />
 <p class="lightbox__caption"></p>
</div>

<script>
(function () {
  var box = document.getElementById('lightbox');
  if (!box) return;
  var img = box.querySelector('img');
  var cap = box.querySelector('.lightbox__caption');
  var last = null;

  function open(src, alt, caption, opener) {
    last = opener;
    img.src = src;
    img.alt = alt || '';
    cap.textContent = caption || '';
    box.classList.add('is-open');
    box.querySelector('.lightbox__close').focus();
  }

  function close() {
    box.classList.remove('is-open');
    img.removeAttribute('src');
    if (last) last.focus();
  }

  document.querySelectorAll('.photo-gallery__item').forEach(function (btn) {
    btn.addEventListener('click', function () {
      var i = btn.querySelector('img');
      open(i.currentSrc || i.src, i.alt, btn.dataset.caption, btn);
    });
  });

  box.addEventListener('click', function (e) {
    if (e.target === box || e.target.closest('.lightbox__close')) close();
  });
  document.addEventListener('keydown', function (e) {
    if (e.key === 'Escape' && box.classList.contains('is-open')) close();
  });

  // Video posters swap themselves for the player only once clicked, so the
  // page makes no request to the video host until the visitor asks for it.
  document.querySelectorAll('.video-card__poster').forEach(function (btn) {
    btn.addEventListener('click', function () {
      var bvid = btn.dataset.bvid;
      if (!bvid) return;
      var wrap = document.createElement('div');
      wrap.className = 'video-card__embed';
      var f = document.createElement('iframe');
      f.src = 'https://player.bilibili.com/player.html?bvid=' + encodeURIComponent(bvid) + '&page=1&autoplay=0';
      f.allowFullscreen = true;
      f.title = btn.getAttribute('aria-label') || 'Video';
      wrap.appendChild(f);
      btn.replaceWith(wrap);
    });
  });
})();
</script>
