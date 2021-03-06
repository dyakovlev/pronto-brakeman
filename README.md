# Pronto runner for Brakeman

[![Code Climate](https://codeclimate.com/github/mmozuras/pronto-brakeman.png)](https://codeclimate.com/github/mmozuras/pronto-brakeman)
[![Build Status](https://travis-ci.org/mmozuras/pronto-brakeman.png)](https://travis-ci.org/mmozuras/pronto-brakeman)
[![Gem Version](https://badge.fury.io/rb/pronto-brakeman.png)](http://badge.fury.io/rb/pronto-brakeman)
[![Dependency Status](https://gemnasium.com/mmozuras/pronto-brakeman.png)](https://gemnasium.com/mmozuras/pronto-brakeman)

Pronto runner for [Brakeman](https://github.com/presidentbeef/brakeman), security vulnerability scanner for RoR. [What is Pronto?](https://github.com/mmozuras/pronto)

## Severity mapping

Brakeman [Confidence](https://github.com/presidentbeef/brakeman#confidence-levels) is mapped to severity levels on the
messages generated by Pronto. High confidence maps to fatal, medium confidence maps to warning, and low confidence maps
to info.
