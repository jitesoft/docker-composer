# Composer

[![Docker Pulls](https://img.shields.io/docker/pulls/jitesoft/composer.svg)](https://hub.docker.com/r/jitesoft/composer)
[![Back project](https://img.shields.io/badge/Open%20Collective-Tip%20the%20devs!-blue.svg)](https://opencollective.com/jitesoft-open-source)

PHP cli and Composer running on alpine linux.

## Tags

All images are built for amd64 and arm64.

### Docker hub

* `jitesoft/composer`
    * `8.0`, `rc`, `unstable`
    * `7.4`, `7`, `stable`, `latest`
    * `7.3`

### GitLab

* `registry.gitlab.com/jitesoft/dockerfiles/composer-alpine`
    * `8.0`, `rc`, `unstable`
    * `7.4`, `7`, `stable`, `latest`
    * `7.3`

### GitHub

* `ghcr.io/jitesoft/composer`
    * `8.0`, `rc`, `unstable`
    * `7.4`, `7`, `stable`, `latest`
    * `7.3`

_Note:  
Earlier versions of this image was built using php-fpm, since 2020-01-01 the image changed to use the CLI image as default._

Dockerfile can be found at [GitLab](https://gitlab.com/jitesoft/dockerfiles/composer-alpine) and [GitHub](https://github.com/Johannestegner/docker-composer-alpine/blob/master/Dockerfile)

### Image labels

This image follows the [Jitesoft image label specification 1.0.0](https://gitlab.com/snippets/1866155).

## Licenses

The files in this repository are released under the MIT License.  
Composer is released under the [MIT](https://github.com/composer/composer/blob/master/LICENSE) license.  
Read the PHP license [here](https://www.php.net/license/index.php).  

## Sponsors

Sponsoring is vital for the further development and maintaining of open source projects.  
Questions and sponsoring queries can be made via <a href="mailto:sponsor@jitesoft.com">email</a>.  
If you wish to sponsor our projects, reach out to the email above or visit any of the following sites:

[Open Collective](https://opencollective.com/jitesoft-open-source)  
[GitHub Sponsors](https://github.com/sponsors/jitesoft)  
[Patreon](https://www.patreon.com/jitesoft)

Jitesoft images are built via GitLab CI on runners hosted by the following wonderful organisations:

<a href="https://www.linaro.org/">
  <img src="https://raw.githubusercontent.com/jitesoft/misc/master/sponsors/linaro.png" width="256" alt="Linaro logo" />
</a>
<a href="https://fosshost.org/">
  <img src="https://raw.githubusercontent.com/jitesoft/misc/master/sponsors/fosshost.png" width="256" alt="Fosshost logo" />
</a>

_The companies above are not affiliated with Jitesoft or any Jitesoft Projects directly._
