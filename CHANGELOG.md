<a name="2.5.0"></a>
# [2.5.0](https://github.com/tinesoft/generator-ngx-library/compare/v2.4.1...v2.5.0) (2017-06-19)


### Bug Fixes

* **template/gulpfile:** correct indentation for `gulp bundle` task ([ecc7091](https://github.com/tinesoft/generator-ngx-library/commit/ecc7091))
* **template/gulpfile:** fix missing `os` and `exec`dependencies in `gulpfile.js` when not skipping styles-related code generation ([2a2bd56](https://github.com/tinesoft/generator-ngx-library/commit/2a2bd56))


### Features

* **demo/meta:** add meaningful meta data to demo/index.html ([3d65755](https://github.com/tinesoft/generator-ngx-library/commit/3d65755))
* **gulp:** allow loading additional gulp tasks put in `./config/gulp-task/*` folder ([62e2565](https://github.com/tinesoft/generator-ngx-library/commit/62e2565))
* **skipDemo:** add option `--skipDemo` to skip generation of demo app related code ([59c3333](https://github.com/tinesoft/generator-ngx-library/commit/59c3333))



<a name="2.4.1"></a>
## [2.4.1](https://github.com/tinesoft/generator-ngx-library/compare/v2.4.0...v2.4.1) (2017-06-05)



<a name="2.4.0"></a>
# [2.4.0](https://github.com/tinesoft/generator-ngx-library/compare/v2.3.0...v2.4.0) (2017-06-05)


### Bug Fixes

* **template/gulpfile:** remove duplicated 'ngc'  gulp task ([2e93bd3](https://github.com/tinesoft/generator-ngx-library/commit/2e93bd3))


### Features

* **skipStyles:** add `--skip-styles` to skip generation of styles inlining related code ([0d8ac6c](https://github.com/tinesoft/generator-ngx-library/commit/0d8ac6c))
* **template/github:** add github's `ISSUE_TEMPLATE.md` file ([6fb36ed](https://github.com/tinesoft/generator-ngx-library/commit/6fb36ed))



<a name="2.3.0"></a>
# [2.3.0](https://github.com/tinesoft/generator-ngx-library/compare/v2.2.0...v2.3.0) (2017-05-31)


### Features

* **compodoc:** add support for compodoc (awesome documentation tool for your Angular projects) ([52d3f9c](https://github.com/tinesoft/generator-ngx-library/commit/52d3f9c))
* **greenkeeper:** add support for greenkeeper (real-time monitoring and automatic updates for npm dependencies) ([f3136a8](https://github.com/tinesoft/generator-ngx-library/commit/f3136a8))



<a name="2.2.0"></a>
# [2.2.0](https://github.com/tinesoft/generator-ngx-library/compare/v2.1.0...v2.2.0) (2017-05-28)


### Bug Fixes

* **devDependencies:** pin dev dependencies to exact versions to avoid build breakages ([30d8e9c](https://github.com/tinesoft/generator-ngx-library/commit/30d8e9c))
* **LICENSE:** set inception year in LICENSE file ([0e996d4](https://github.com/tinesoft/generator-ngx-library/commit/0e996d4))


### Features

* **tests:** add `karma-jasmine-html-reporter` for tests results output in browser ([cba12cf](https://github.com/tinesoft/generator-ngx-library/commit/cba12cf))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/tinesoft/generator-ngx-library/compare/v2.0.1...v2.1.0) (2017-05-06)


### Features

* **release:** add pre-release checks to ensure library is ready to be released ([b67fd55](https://github.com/tinesoft/generator-ngx-library/commit/b67fd55))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/tinesoft/generator-ngx-library/compare/v2.0.0...v2.0.1) (2017-05-03)


### Bug Fixes

* **peerDependencies:** align some angular and typescript dev dependencies with angular v4+ ([6b7f3cb](https://github.com/tinesoft/generator-ngx-library/commit/6b7f3cb)), closes [#1](https://github.com/tinesoft/generator-ngx-library/issues/1)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/tinesoft/generator-ngx-library/compare/v1.0.1...v2.0.0) (2017-05-01)


### Features

* **all:** migrate to angular ([a2d9a4b](https://github.com/tinesoft/generator-ngx-library/commit/a2d9a4b))


### BREAKING CHANGES

* **all:** - rename package from `generator-ng-plugin` to `generator-ngx-library`
- migrate from AngularJS to Angular
- migrate from `Grunt` to `Gulp`



<a name="1.0.1"></a>
## [1.0.1](https://github.com/tinesoft/generator-ngx-library/compare/42c574e...v1.0.1) (2015-09-24)


### Bug Fixes

* **coveralls:** fix integration of code coverage tool(coveralls) in the build system ([7d40c70](https://github.com/tinesoft/generator-ngx-library/commit/7d40c70))


### Features

* **all:** initial commit ([42c574e](https://github.com/tinesoft/generator-ngx-library/commit/42c574e))



