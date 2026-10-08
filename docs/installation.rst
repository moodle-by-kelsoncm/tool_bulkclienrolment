Instalação
==========

Passo a Passo
-------------

1. Acesse o diretório de ferramentas administrativas do Moodle:

   .. code-block:: bash

      cd /caminho/do/moodle/admin/tool

2. Clone o repositório nomeando a pasta como `bulkclienrolment`:

   .. code-block:: bash

      git clone https://github.com/moodle-by-kelsoncm/tool_bulkclienrolment.git bulkclienrolment

3. Execute o script de atualização via linha de comando do Moodle:

   .. code-block:: bash

      php admin/cli/upgrade.php --non-interactive
