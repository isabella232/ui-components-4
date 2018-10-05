# Angular UI Components for ManageIQ

Note: As of [#349](https://github.com/ManageIQ/ui-components/pull/349), the `bower-dev` branch is no longer updated.

---

The ManageIQ/ui-components repository is used to provide shared UI components for the various ManageIQ UIs.

---

Any development happens on the `master` branch, the `bower-dev` branch is automatically generated from any `master` commit with green Travis.

The purpose of this `bower-dev` branch is to contain built `dist/css/` and `dist/js/` for use by bower.

Any new bower-released version would be tagged on this branch, and any projects which previously used the `master` branch with bower will need to use this one instead.

(Please note however, that bower support will be discontinued as soon as practical.)

---

Please do not update this branch manually.
