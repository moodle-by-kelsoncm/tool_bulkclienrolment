# Instalação — moodle-tool_bulkclienrolment

## Procedimento de Instalação

1. Clone o repositório no diretório de ferramentas de administração do Moodle:
   ```bash
   cd /caminho/do/moodle/admin/tool
   git clone https://github.com/moodle-by-kelsoncm/moodle-tool_bulkclienrolment.git bulkclienrolment
   ```
2. Execute a atualização via CLI:
   ```bash
   php admin/cli/upgrade.php --non-interactive
   ```
