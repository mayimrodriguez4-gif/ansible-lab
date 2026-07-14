# Laboratorio Docker + Ansible

## Objetivo

Crear dos servidores Linux utilizando Docker y administrarlos mediante Ansible.

---

## Iniciar los contenedores

```bash
docker compose up -d
```

---

## Verificar los contenedores

```bash
docker ps
```

---

## Ejecutar el playbook

```bash
ansible-playbook -i inventory.ini playbook.yml
```

---

## Archivos del proyecto

```
ansible-lab/
├── docker-compose.yml
├── inventory.ini
├── playbook.yml
└── README.md
```

---

## Evidencia

Agregar una captura de pantalla donde se observe la ejecución exitosa del playbook.