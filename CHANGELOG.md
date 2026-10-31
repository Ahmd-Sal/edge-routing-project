# Changelog

## [1.1.1](https://github.com/Ahmd-Sal/edge-routing-project/compare/go-api@1.1.0...go-api@1.1.1) (2026-10-31)


### Chores

* add chores and revert sections to the changelog[skip ci] ([#48](https://github.com/Ahmd-Sal/edge-routing-project/issues/48)) ([8e6108f](https://github.com/Ahmd-Sal/edge-routing-project/commit/8e6108ff8789c2139c1b2af08c4018d63a858a65))
* correct file name [skip ci] ([#44](https://github.com/Ahmd-Sal/edge-routing-project/issues/44)) ([27d8060](https://github.com/Ahmd-Sal/edge-routing-project/commit/27d80602246954c91303f6a19c31a311e46ed6c7))
* **monitoring:** add Prometheus, Grafana, and cAdvisor stack ([#49](https://github.com/Ahmd-Sal/edge-routing-project/issues/49)) ([62c8903](https://github.com/Ahmd-Sal/edge-routing-project/commit/62c8903f0279395b9e84a93979965e5e924e4b6d))
* update hit-counter image version to 1.1.0 ([#47](https://github.com/Ahmd-Sal/edge-routing-project/issues/47)) ([9412448](https://github.com/Ahmd-Sal/edge-routing-project/commit/941244898c53aa4f3b6cb03e73ee0c39cb05b9a5))

## [1.1.0](https://github.com/Ahmd-Sal/edge-routing-project/compare/go-api@1.0.0...go-api@1.1.0) (2026-10-28)


### Features

* **api:** implement HTTP web server with logging ([6b09d87](https://github.com/Ahmd-Sal/edge-routing-project/commit/6b09d87d8e568ebd610b7be2169eec6f9996ddc7))
* **api:** implement HTTP web server with logging ([8167894](https://github.com/Ahmd-Sal/edge-routing-project/commit/8167894e4fdaf830956090e3c51cf6409c5440c2))
* **backend:** add an atomic hit counter to the root path ([#8](https://github.com/Ahmd-Sal/edge-routing-project/issues/8)) ([7502956](https://github.com/Ahmd-Sal/edge-routing-project/commit/7502956dda91e8110a096785f4fa42c6e501f068))
* **backend:** customize instance identification via environme… ([#7](https://github.com/Ahmd-Sal/edge-routing-project/issues/7)) ([4fa9b40](https://github.com/Ahmd-Sal/edge-routing-project/commit/4fa9b4050a99a22d2250b6fbcb4d8b0475c1307c))
* **ci:** add release-please ([#36](https://github.com/Ahmd-Sal/edge-routing-project/issues/36)) ([2181742](https://github.com/Ahmd-Sal/edge-routing-project/commit/2181742c6b8b08f2c165e52b1aa6bc75005de91f))
* **docker:** add multi-container orchestration with Docker Compose ([3c905ef](https://github.com/Ahmd-Sal/edge-routing-project/commit/3c905ef454d7260518fac91b9626d3c15a6d4ed6))
* **docker:** add multi-container orchestration with Docker Compose ([a48a70f](https://github.com/Ahmd-Sal/edge-routing-project/commit/a48a70f7554778ae01d6b5f0dcd9382aca8868c3))
* **nginx:** configure Nginx for SSL termination and backend proxying ([#5](https://github.com/Ahmd-Sal/edge-routing-project/issues/5)) ([60a53c8](https://github.com/Ahmd-Sal/edge-routing-project/commit/60a53c803140a0c97e068961c44c963129978db6))
* **nginx:** make nginx handle the favicon request instead of the backend ([#11](https://github.com/Ahmd-Sal/edge-routing-project/issues/11)) ([f4c7860](https://github.com/Ahmd-Sal/edge-routing-project/commit/f4c7860eff99855fdab53ffb296f05ac74858a1b))


### Bug Fixes

* **backend:** clean up health handler execution logic ([#9](https://github.com/Ahmd-Sal/edge-routing-project/issues/9)) ([29f445b](https://github.com/Ahmd-Sal/edge-routing-project/commit/29f445bed023e4a5035b4ca4411265bb99dcad2c))
* **router:** prevent catch-all route matching on root and health handler ([#6](https://github.com/Ahmd-Sal/edge-routing-project/issues/6)) ([b7d4c5a](https://github.com/Ahmd-Sal/edge-routing-project/commit/b7d4c5ae523b95d9a07ceffb4ee4e22cb138b512))
