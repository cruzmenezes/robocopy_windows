# ROBOCOPY

### Copia dados de um arquivo de um local para outro.

#### Syntax
```
ROBOCOPY <source> <destination> [<options>]
```
#### Exemplo:
   
ROBOCOPY "C:\Users\Edson_Victor\Desktop\bkp" "L:\robocopy" *.*/E /copyall 
robocopy "L:\robocopy" "L:\copy_robocopy" /E /LOG:L:\copy_robocopy\logs\teste_logs.txt


*.* copia todos arquivos e diretorios. 
/e	Copia subdiretórios. Essa opção inclui automaticamente os diretórios vazios.
/log:<logfile>	Grava a saída de status no arquivo de log (substitui o arquivo de log existente).
/copyall Copia tudo.

### Considerações
sobre robocopy
- O comando pode ser executado via CMD com privilegio de administrativo ou o mesmo pode
salva o comando em um arquivo com a extensão .bat e para automatiza você pode fazer 
o agendamento no (AGENDAMENTO DE TAREFA DO WINDOWS). 



