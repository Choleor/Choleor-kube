# Choleor-kube
### Choreography Generator Service
인공지능을 기반으로 사용자가 원하는 노래에 맞춰 새로운 안무 variation을 제공하는 웹 서비스 choleor의<br>
kubernetes object 관련 레포지토리입니다.<br>

## 📌 Server Architecture
Choleor 서비스는 MSA를 도입하여 audio, choreo, product 총 3개의 서버로 분리하였으며 전반적인 아키텍쳐는 다음과 같습니다.<br>
<a href="https://ibb.co/zHWgCJh"><img src="https://i.ibb.co/JFWT8QR/diagram.png" alt="diagram" border="0"></a>

## 🧑‍🤝‍🧑 Main Member
### Jihee Seon
- Dockerize system
- Monitor media handling performance
  - Scale up-down
- Design architecture
- Support Kubernetes cluster handling

## 👨‍⚕️ Contributor
### Junghun Yang
- In charge of managing kubernetes cluster
- Build Kubernetes Object
- Configure Nginx Ingress Controller
- Introduce HTTP 2.0 (TLS)
- Scale up-down
