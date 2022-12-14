---
layout: docs
title: Tovuti Action Bar
description: Learn about the guiding principles, strategies, and techniques used to build and maintain Bootstrap so you can more easily customize and extend it yourself.
group: extend
aliases:
  - "/docs/5.2/extend/"
---


## Summary


## Example

{{< example >}}
<div class="tov-content-actionbar" style="background-color: var(--bs-gray-400)">
  <div class="btn-toolbar p-3 gap-2" role="toolbar" aria-label="Toolbar" id="toolbar">
    <div class="btn-wrapper flex gx-2" id="toolbar-new">
      <button
        class="btn button-new btn-success btn-sm d-inline-flex align-items-center gap-2"
        type="button"
      >
        <i class="fa-solid fa-circle-plus" aria-hidden="true"></i>New
      </button>
    </div>
    <div class="btn-wrapper" id="toolbar-publish">
      <button
        class="btn button-publish btn-brand-white btn-sm d-inline-flex align-items-center gap-2"
        type="button"
      >
        <i class="fa-solid fa-circle-check text-success" aria-hidden="true"></i>Publish
      </button>
    </div>
    <div class="btn-wrapper" id="toolbar-unpublish">
      <button
        class="btn btn-unpublish btn-brand-white btn-sm d-inline-flex align-items-center gap-2"
        type="button"
      >
        <i class="fa-solid fa-circle-xmark text-warning" aria-hidden="true"></i>Unpublish
      </button>
    </div>
    <div class="btn-wrapper" id="toolbar-delete">
      <button
        class="btn btn-delete btn-brand-white btn-sm d-inline-flex align-items-center gap-2"
        type="button"
      >
        <i class="fa-solid fa-trash text-danger" aria-hidden="true"></i>Delete
      </button>
    </div>
    <div class="btn-wrapper" id="toolbar-clone">
      <button
        class="btn btn-clone btn-brand-white btn-sm d-inline-flex align-items-center gap-2"
        type="button"
      >
        <i class="fa-solid fa-clone" aria-hidden="true"></i>Clone Course(s)
      </button>
    </div>
    <div class="btn-wrapper ms-auto" id="toolbar-history">
      <button
        class="btn btn-clone btn-brand-white btn-sm d-inline-flex align-items-center gap-2"
        type="button"
      >
        <i class="fa-solid fa-rectangle-history-circle-user" aria-hidden="true"></i>Change History
      </button>
    </div>
  </div>
</div>

{{< /example >}}
