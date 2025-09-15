# Facu Importaciones - Infraestructura Docker

Infraestructura completa con servicios dockerizados para Facu Importaciones.

## 🌐 Red y Dominios

- **Dominio:** `facuint.org`
- **Subdominios:** `*.facuint.org` 
- **SSL:** Certificados automáticos via CloudFlare DNS
- **Red Docker:** `proxy` network para comunicación interna

## 🔒 Seguridad

- SSL/TLS automático con Let's Encrypt
- CrowdSec con whitelist de IPs confiables
- Traefik con middleware de seguridad
- Red interna aislada
