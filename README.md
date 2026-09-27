# Lista 03 - Classes e pacotes

## Solução

Carro com modelo e cor públicos; Sistema instancia dois carros e chama buzinar().

O PDF se chama Lista 03, mas o título interno é Missão 02. A numeração da entrega segue o nome do arquivo.

## Executar

Requisito: JDK 17 ou superior, com java e javac disponíveis no terminal.
Extraia o ZIP e abra esta pasta no VS Code. Abra apenas uma lista por janela,
pois as listas 03 e 04 usam os mesmos nomes de classes em versões diferentes.

No terminal, dentro desta pasta:

```bash
mkdir -p bin
javac -encoding UTF-8 -d bin @fontes.txt
java -cp bin br.com.meusistema.main.Sistema
```

No Windows, também é possível executar `executar.bat` pelo terminal.
No Git Bash ou Linux: `bash executar.sh`.
Os scripts compilam as fontes; não instalam o JDK.

## Enviar ao GitHub

Crie um repositório vazio para esta lista. Extraia o ZIP e envie o conteúdo
desta pasta, incluindo src, README.md, fontes.txt e .gitignore.
Não envie apenas o ZIP: os arquivos Java devem aparecer no repositório.

No Git Bash, dentro desta pasta:

```bash
git init
git add .
git commit -m "feat: resolve lista 03 de POO"
git branch -M main
git remote add origin URL_DO_REPOSITORIO
git push -u origin main
```

Substitua URL_DO_REPOSITORIO pela URL do repositório vazio que você criou.
Se usar um repositório que já existe localmente, mantenha o remoto e o
histórico atuais e use apenas git add, git commit e git push.
Ao final, copie o link do repositório para a entrega da disciplina.

## Fonte

[Lista 03 POO.pdf](https://drive.google.com/file/d/14nczWvu6thGnGeO-xqp_rpeSWOzb_BAe/view).

## Validação

Fontes compiladas com Java 17 e -Xlint:all, sem avisos. A saída real da classe principal está em RESULTADO_EXECUCAO.txt. Os arquivos compilados não fazem parte desta entrega.
