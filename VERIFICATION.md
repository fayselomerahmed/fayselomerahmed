# Portfolio verification

The public showcase contains two iOS projects and their supporting curriculum service. Earlier exercises and predecessor apps are retained privately rather than presented as additional finished products.

## Verified engineering evidence

| Project | Passing hosted checks |
| --- | --- |
| [Deutsch B1 Coach](https://github.com/fayselomerahmed/deutsch-b1-coach-ios) | [Release simulator build, 78 iOS tests, 7 core tests](https://github.com/fayselomerahmed/deutsch-b1-coach-ios/actions/runs/39037289889) |
| [Travel Companion](https://github.com/fayselomerahmed/travel-companion-ios) | [Release simulator build and 5 tests](https://github.com/fayselomerahmed/travel-companion-ios/actions/runs/39037288743) |
| [Curriculum Studio](https://github.com/fayselomerahmed/deutsch-b1-coach-studio) | [Clean install, production build, 11 checks, type checking, linting, and production-dependency audit](https://github.com/fayselomerahmed/deutsch-b1-coach-studio/actions/runs/39037286238) |

These are concrete checks of personal-project source, not claims of commercial deployment, customer numbers, or App Store release. A simulator build does not replace physical-device, accessibility, service-integration, or release-signing checks.

## Release boundaries

- **Deutsch B1 Coach:** the bundled learning experience works offline. Optional remote services require a separately configured HTTPS deployment. Physical-device speech, StoreKit, content/teacher review, and model/runtime redistribution checks remain release requirements.
- **Travel Companion:** live integrations need provider configuration. Travel information is advisory; missing requirements are not interpreted as permission to travel. Incomplete premium capabilities are not sold as finished features.
- **Curriculum Studio:** production deployment needs a trusted identity gateway or independently verified sessions, staging D1 recovery/authorization checks, and resolution or review of the documented upstream build-tool advisories.

Detailed checklists remain with each source repository: [Deutsch](https://github.com/fayselomerahmed/deutsch-b1-coach-ios/blob/main/PRODUCTION_READINESS.md), [Travel](https://github.com/fayselomerahmed/travel-companion-ios/blob/main/PRODUCTION_READINESS.md), [Studio](https://github.com/fayselomerahmed/deutsch-b1-coach-studio/blob/main/PRODUCTION_READINESS.md).

Third-party notices and contributor credits stay with the source. Language levels on the profile are self-reported; no language certificate or work authorization is implied.
