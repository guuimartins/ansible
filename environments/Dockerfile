FROM quay.io/ansible/awx-ee

USER root

# Instalar a coleção community.general
RUN ansible-galaxy collection install community.general

# Instalar dependências adicionais, se necessário
RUN pip install proxmoxer requests

