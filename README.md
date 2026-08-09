# 🔥 Guía práctica de firewalls para estudiantes 
## Practical Firewall Guide for Cybersecurity Students (Router Version)

<!-- BILINGUAL BADGES / BADGES BILINGÜES -->
![Español](https://img.shields.io/badge/Idioma-Español-red)
![English](https://img.shields.io/badge/Language-English-blue)

---
# 💡 Por qué empezar aquí
No necesitas un laboratorio caro para aprender firewalls de verdad: el router que tu proveedor de fibra óptica te dio ya trae uno integrado (tipo Stateful). Entender sus opciones es el primer paso real hacia pfSense, Cisco ASA o cualquier NGFW empresarial: la lógica —tráfico entrante vs. saliente, puertos, NAT— es la misma.

## Why start here
You don't need an expensive lab to really learn firewalls: the router your fiber optic provider gave you already has one built-in (Stateful type). Understanding its options is the first real step toward pfSense, Cisco ASA, or any enterprise NGFW: the logic —incoming vs. outgoing traffic, ports, NAT— is the same.

---
# 🔐 ¿Qué es un firewall?
Un firewall (o cortafuegos) es un sistema de seguridad —de hardware, de software, o ambos— diseñado para controlar y monitorear el tráfico de red entrante y saliente. Su función principal es actuar como una barrera de protección entre una red interna segura (tu casa, tu laboratorio, la oficina) y redes externas no confiables, como Internet. Bloquea accesos no autorizados, malware y ciberataques, mientras permite pasar el tráfico legítimo.

## What is a firewall?
A firewall is a security system—hardware, software, or both—designed to control and monitor incoming and outgoing network traffic. Its main function is to act as a protective barrier between a secure internal network (your home, your laboratory, the office) and untrusted external networks, such as the Internet. Blocks unauthorized access, malware and cyber attacks, while allowing legitimate traffic to pass through.

---

# 💻 El equipo de estudio: un router de fibra óptica
Para esta guía usamos como ejemplo un Fios Router de Verizon, el router que la propia compañía de fibra óptica entrega integrado con el servicio (combina módem ONT + router + firewall en un solo equipo). Este tipo de router es representativo de la mayoría de equipos ISP actuales (Movistar, Claro, AT&T, etc.): todos exponen un panel web con secciones muy similares: General, Access Control, Port Forwarding, Port Triggering, DMZ Host, Remote Administration, Static NAT y Security Log.

## The study equipment: a fiber-optic router
For this guide, we use as an example a Verizon Fios Router, the router that the fiber optic company itself provides integrated with the service (combines ONT modem + router + firewall in a single device). This type of router is representative of most current ISP equipment (Movistar, Claro, AT&T, etc.): they all expose a web panel with very similar sections: General, Access Control, Port Forwarding, Port Triggering, DMZ Host, Remote Administration, Static NAT, and Security Log.



