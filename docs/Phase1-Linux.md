\# Phase 1 - Linux Infrastructure 구축



\## 프로젝트 목표



GPUaaS 환경 구축을 위한 Linux 인프라를 구성한다.



\---



\## 구성도



| Hostname | IP | 역할 |

|-----------|--------------|----------|

| gpu-master.lab | 192.168.56.10 | Master Node |

| gpu-worker1.lab | 192.168.56.11 | Worker Node |

| gpu-worker2.lab | 192.168.56.12 | Worker Node |

| gpu-storage.lab | 192.168.56.13 | Storage Node |



\---



\## 수행 내용



\- Rocky Linux 9 Minimal 설치

\- Hostname 설정

\- Static IP 설정

\- /etc/hosts 구성

\- SSH Key 기반 로그인

\- Time Sync 설정

\- firewalld 비활성화

\- SELinux permissive 설정



\---



\## 사용 명령어



hostnamectl



timedatectl



ssh-keygen



ssh-copy-id



systemctl



getenforce



setenforce



\---



\## 배운 점



\- 여러 서버 간 SSH Key 인증 구성

\- Linux 서버 기본 운영 환경 구축

\- Kubernetes 구축 전 필요한 초기 작업 이해



