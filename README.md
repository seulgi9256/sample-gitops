# sample-gitops

sample-api를 위한 gitops 프로젝트. 각각 blue-green, canary, rolling update(이상 argo-rollouts 플러그인), rolling update(deployment)를 이용한 배포 샘플 프로젝트입니다.

자세한 내용은 소스코드를 참고하시기 바랍니다

프로젝트 구조

```bash
.
├── README.md
└── sample-api
    ├── blue-green                       # rollout 기반 blue-green 배포정책
    ├── canary                           # rollout 기반 canary 배포정책
    ├── rolling-update                   # rollout 기반 rolling update 배포정책
    └── rolling-update-with-deployment   # 위까지는 istio기반 배포정책
    └── rolling-update-no-istio          # istio기반이 아닌 rolling update deployment
```
