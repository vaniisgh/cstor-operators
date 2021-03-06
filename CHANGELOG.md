* # Changelog

## [v1.10.0](https://github.com/openebs/cstor-operators/tree/v1.10.0) (2020-05-15)

**Merged pull requests:**

- fix\(cspi\): remove finalizer on claim of blockdevice which underwent replacement [\#72](https://github.com/openebs/cstor-operators/pull/72) ([mittachaitu](https://github.com/mittachaitu))
- chore\(log\): add more information in error event \(\#68\) [\#69](https://github.com/openebs/cstor-operators/pull/69) ([mittachaitu](https://github.com/mittachaitu))
- fix\(Makefile\): update the expression to trim 'v' from tag [\#64](https://github.com/openebs/cstor-operators/pull/64) ([prateekpandey14](https://github.com/prateekpandey14))
- refact\(build\): fix cstor base image tag [\#62](https://github.com/openebs/cstor-operators/pull/62) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(push\_script\): refactor makefile and push scirpt [\#59](https://github.com/openebs/cstor-operators/pull/59) ([sonasingh46](https://github.com/sonasingh46))
- refact\(build\): updating makefile to verify go mod files [\#58](https://github.com/openebs/cstor-operators/pull/58) ([mynktl](https://github.com/mynktl))
- add travis sanity check [\#54](https://github.com/openebs/cstor-operators/pull/54) ([sonasingh46](https://github.com/sonasingh46))
- feat\(policy\): reconcile volume policy per volume bases [\#52](https://github.com/openebs/cstor-operators/pull/52) ([prateekpandey14](https://github.com/prateekpandey14))
- refact\(webhook\): update the admission service and config name [\#51](https://github.com/openebs/cstor-operators/pull/51) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(operator\): use single service account for deployments [\#50](https://github.com/openebs/cstor-operators/pull/50) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(refactor\) : add fake controller testing for cspc-operator [\#49](https://github.com/openebs/cstor-operators/pull/49) ([sonasingh46](https://github.com/sonasingh46))
- fix\(deps\): remove indirect version dependency to openebs/api [\#48](https://github.com/openebs/cstor-operators/pull/48) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(webhook\): add volume specific webhook validations [\#47](https://github.com/openebs/cstor-operators/pull/47) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(webhook\): add cspc expansion validations [\#46](https://github.com/openebs/cstor-operators/pull/46) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(ci\): add travis ci to build and push [\#45](https://github.com/openebs/cstor-operators/pull/45) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(build\): make image tags with amd64 for amd64 builds [\#44](https://github.com/openebs/cstor-operators/pull/44) ([sonasingh46](https://github.com/sonasingh46))
- fix\(ci\): refactor github actions and Makefile targets [\#42](https://github.com/openebs/cstor-operators/pull/42) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(volume replica\): add snapshot information in CVR status [\#41](https://github.com/openebs/cstor-operators/pull/41) ([mittachaitu](https://github.com/mittachaitu))
- Automate the CRD generate with OpenAPIV3 validation [\#38](https://github.com/openebs/cstor-operators/issues/38)
- chore\(vendor\): update vendor to include builder function changes [\#33](https://github.com/openebs/cstor-operators/pull/33) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspc\): refactor cspc reconcile and cleanup [\#30](https://github.com/openebs/cstor-operators/pull/30) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspi conditions\): add cspi condition to represent the pool operations [\#31](https://github.com/openebs/cstor-operators/pull/31) ([mittachaitu](https://github.com/mittachaitu))
- refact\(cspc\): add tests and constants for cspc conditions [\#29](https://github.com/openebs/cstor-operators/pull/29) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cstor-operators\): update vendor in accordance with latest apis [\#28](https://github.com/openebs/cstor-operators/pull/28) ([sonasingh46](https://github.com/sonasingh46))
- fix\(cspi\): pool create with compression as filesystem property [\#27](https://github.com/openebs/cstor-operators/pull/27) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cspi\): add capability to set compression on cstor pool [\#26](https://github.com/openebs/cstor-operators/pull/26) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspc\): add cspi instances details on cspc status [\#25](https://github.com/openebs/cstor-operators/pull/25) ([sonasingh46](https://github.com/sonasingh46))
- fix\(cspi, status\): fix CSPI status to represent capacity and Phase of pool [\#24](https://github.com/openebs/cstor-operators/pull/24) ([mittachaitu](https://github.com/mittachaitu))
- chore\(cvc\): refactor cvc controller to use cstorvolumeconfig [\#23](https://github.com/openebs/cstor-operators/pull/23) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(operator\): make openebs service account configurable for pool and volume deployments [\#22](https://github.com/openebs/cstor-operators/pull/22) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(cstor-operators\): update vendor with latest cstor apis [\#21](https://github.com/openebs/cstor-operators/pull/21) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cstor\_pool\_apis\): update code to use updated cStor pool APIs [\#20](https://github.com/openebs/cstor-operators/pull/20) ([mittachaitu](https://github.com/mittachaitu))
- feat\(cspc\): add reconciliation for cspc tunables [\#19](https://github.com/openebs/cstor-operators/pull/19) ([sonasingh46](https://github.com/sonasingh46))
- feat\(operators\): add operator, rbac rules and volume crds yamls [\#18](https://github.com/openebs/cstor-operators/pull/18) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(cvc\): refactor volume and pool provisioning including updated image names [\#17](https://github.com/openebs/cstor-operators/pull/17) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(yaml\): update poolConfig fields in examples [\#16](https://github.com/openebs/cstor-operators/pull/16) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(roThresholdLimit\): add ROThresholdLimit support in pool manager [\#15](https://github.com/openebs/cstor-operators/pull/15) ([mittachaitu](https://github.com/mittachaitu))
- refact\(webhook\): add validation for new fields in cspc [\#14](https://github.com/openebs/cstor-operators/pull/14) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(cvr\): add volume replica controller using new APIs [\#13](https://github.com/openebs/cstor-operators/pull/13) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(build\): add makefile target and Dockerfile for cstor webhook [\#12](https://github.com/openebs/cstor-operators/pull/12) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(build\): add github actions to run test and build [\#11](https://github.com/openebs/cstor-operators/pull/11) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(dockerfile\): use updated binary names for pool and volume manger [\#10](https://github.com/openebs/cstor-operators/pull/10) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(cspi-controller\): add writecache functionality with latest schema changes in CSPI [\#9](https://github.com/openebs/cstor-operators/pull/9) ([mittachaitu](https://github.com/mittachaitu))
- feat\(webhook\): add cstor-webhook using openebs/api changes [\#8](https://github.com/openebs/cstor-operators/pull/8) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(build\): add makefile tagets and Dockerfiles for all controllers [\#7](https://github.com/openebs/cstor-operators/pull/7) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cv\): add cstor volume manager/controller using new APIs [\#6](https://github.com/openebs/cstor-operators/pull/6) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cspc-operator\): use lease apis to enable leader election [\#5](https://github.com/openebs/cstor-operators/pull/5) ([sonasingh46](https://github.com/sonasingh46))
- feat\(cvc\): use openebs/api lease apis for leaderelection [\#4](https://github.com/openebs/cstor-operators/pull/4) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(build\): add license in build scripts [\#3](https://github.com/openebs/cstor-operators/pull/3) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cvc\): add cstorvolumeclaim operator using new apis [\#2](https://github.com/openebs/cstor-operators/pull/2) ([prateekpandey14](https://github.com/prateekpandey14))
- add cspc-operator  [\#1](https://github.com/openebs/cstor-operators/pull/1) ([sonasingh46](https://github.com/sonasingh46))


## [v1.10.0-RC2](https://github.com/openebs/cstor-operators/tree/v1.10.0-RC2) (2020-05-13)

**Merged pull requests:**

- fix\(cspi\): remove finalizer on claim of blockdevice which underwent replacement [\#72](https://github.com/openebs/cstor-operators/pull/72) ([mittachaitu](https://github.com/mittachaitu))
- chore\(log\): add more information in error event \(\#68\) [\#69](https://github.com/openebs/cstor-operators/pull/69) ([mittachaitu](https://github.com/mittachaitu))

## [v1.10.0-RC1](https://github.com/openebs/cstor-operators/tree/v1.10.0-RC1) (2020-05-08)

**Merged pull requests:**

- fix\(Makefile\): update the expression to trim 'v' from tag [\#64](https://github.com/openebs/cstor-operators/pull/64) ([prateekpandey14](https://github.com/prateekpandey14))
- refact\(build\): fix cstor base image tag [\#62](https://github.com/openebs/cstor-operators/pull/62) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(push\_script\): refactor makefile and push scirpt [\#59](https://github.com/openebs/cstor-operators/pull/59) ([sonasingh46](https://github.com/sonasingh46))
- refact\(build\): updating makefile to verify go mod files [\#58](https://github.com/openebs/cstor-operators/pull/58) ([mynktl](https://github.com/mynktl))
- chore(travis): add travis sanity check [\#54](https://github.com/openebs/cstor-operators/pull/54) ([sonasingh46](https://github.com/sonasingh46))
- feat\(policy\): reconcile volume policy per volume bases [\#52](https://github.com/openebs/cstor-operators/pull/52) ([prateekpandey14](https://github.com/prateekpandey14))
- refact\(webhook\): update the admission service and config name [\#51](https://github.com/openebs/cstor-operators/pull/51) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(operator\): use single service account for deployments [\#50](https://github.com/openebs/cstor-operators/pull/50) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(refactor\) : add fake controller testing for cspc-operator [\#49](https://github.com/openebs/cstor-operators/pull/49) ([sonasingh46](https://github.com/sonasingh46))
- fix\(deps\): remove indirect version dependency to openebs/api [\#48](https://github.com/openebs/cstor-operators/pull/48) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(webhook\): add volume specific webhook validations [\#47](https://github.com/openebs/cstor-operators/pull/47) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(webhook\): add cspc expansion validations [\#46](https://github.com/openebs/cstor-operators/pull/46) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(ci\): add travis ci to build and push [\#45](https://github.com/openebs/cstor-operators/pull/45) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(build\): make image tags with amd64 for amd64 builds [\#44](https://github.com/openebs/cstor-operators/pull/44) ([sonasingh46](https://github.com/sonasingh46))
- fix\(ci\): refactor github actions and Makefile targets [\#42](https://github.com/openebs/cstor-operators/pull/42) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(volume replica\): add snapshot information in CVR status [\#41](https://github.com/openebs/cstor-operators/pull/41) ([mittachaitu](https://github.com/mittachaitu))
- feat(apis): Automate the CRD generate with OpenAPIV3 validation [\#38](https://github.com/openebs/cstor-operators/issues/38) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(vendor\): update vendor to include builder function changes [\#33](https://github.com/openebs/cstor-operators/pull/33) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspc\): refactor cspc reconcile and cleanup [\#30](https://github.com/openebs/cstor-operators/pull/30) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspi conditions\): add cspi condition to represent the pool operations [\#31](https://github.com/openebs/cstor-operators/pull/31) ([mittachaitu](https://github.com/mittachaitu))
- refact\(cspc\): add tests and constants for cspc conditions [\#29](https://github.com/openebs/cstor-operators/pull/29) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cstor-operators\): update vendor in accordance with latest apis [\#28](https://github.com/openebs/cstor-operators/pull/28) ([sonasingh46](https://github.com/sonasingh46))
- fix\(cspi\): pool create with compression as filesystem property [\#27](https://github.com/openebs/cstor-operators/pull/27) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cspi\): add capability to set compression on cstor pool [\#26](https://github.com/openebs/cstor-operators/pull/26) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspc\): add cspi instances details on cspc status [\#25](https://github.com/openebs/cstor-operators/pull/25) ([sonasingh46](https://github.com/sonasingh46))
- fix\(cspi, status\): fix CSPI status to represent capacity and Phase of pool [\#24](https://github.com/openebs/cstor-operators/pull/24) ([mittachaitu](https://github.com/mittachaitu))
- chore\(cvc\): refactor cvc controller to use cstorvolumeconfig [\#23](https://github.com/openebs/cstor-operators/pull/23) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(operator\): make openebs service account configurable for pool and volume deployments [\#22](https://github.com/openebs/cstor-operators/pull/22) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(cstor-operators\): update vendor with latest cstor apis [\#21](https://github.com/openebs/cstor-operators/pull/21) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cstor\_pool\_apis\): update code to use updated cStor pool APIs [\#20](https://github.com/openebs/cstor-operators/pull/20) ([mittachaitu](https://github.com/mittachaitu))
- feat\(cspc\): add reconciliation for cspc tunables [\#19](https://github.com/openebs/cstor-operators/pull/19) ([sonasingh46](https://github.com/sonasingh46))
- feat\(operators\): add operator, rbac rules and volume crds yamls [\#18](https://github.com/openebs/cstor-operators/pull/18) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(cvc\): refactor volume and pool provisioning including updated image names [\#17](https://github.com/openebs/cstor-operators/pull/17) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(yaml\): update poolConfig fields in examples [\#16](https://github.com/openebs/cstor-operators/pull/16) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(roThresholdLimit\): add ROThresholdLimit support in pool manager [\#15](https://github.com/openebs/cstor-operators/pull/15) ([mittachaitu](https://github.com/mittachaitu))
- refact\(webhook\): add validation for new fields in cspc [\#14](https://github.com/openebs/cstor-operators/pull/14) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(cvr\): add volume replica controller using new APIs [\#13](https://github.com/openebs/cstor-operators/pull/13) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(build\): add makefile target and Dockerfile for cstor webhook [\#12](https://github.com/openebs/cstor-operators/pull/12) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(build\): add github actions to run test and build [\#11](https://github.com/openebs/cstor-operators/pull/11) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(dockerfile\): use updated binary names for pool and volume manger [\#10](https://github.com/openebs/cstor-operators/pull/10) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(cspi-controller\): add writecache functionality with latest schema changes in CSPI [\#9](https://github.com/openebs/cstor-operators/pull/9) ([mittachaitu](https://github.com/mittachaitu))
- feat\(webhook\): add cstor-webhook using openebs/api changes [\#8](https://github.com/openebs/cstor-operators/pull/8) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(build\): add makefile tagets and Dockerfiles for all controllers [\#7](https://github.com/openebs/cstor-operators/pull/7) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cv\): add cstor volume manager/controller using new APIs [\#6](https://github.com/openebs/cstor-operators/pull/6) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cspc-operator\): use lease apis to enable leader election [\#5](https://github.com/openebs/cstor-operators/pull/5) ([sonasingh46](https://github.com/sonasingh46))
- feat\(cvc\): use openebs/api lease apis for leaderelection [\#4](https://github.com/openebs/cstor-operators/pull/4) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(build\): add license in build scripts [\#3](https://github.com/openebs/cstor-operators/pull/3) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cvc\): add cstorvolumeclaim operator using new apis [\#2](https://github.com/openebs/cstor-operators/pull/2) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(cspc\): add cspc-operator using new apis  [\#1](https://github.com/openebs/cstor-operators/pull/1) ([sonasingh46](https://github.com/sonasingh46))

