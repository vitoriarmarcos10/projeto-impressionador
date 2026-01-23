# projeto-impressionador
Repositório criado para manipular,praticar o Git e GitHub.
Aprendendo a trabalhar com repositório remoto


-- LISTA DE COMANDOS APRENDIDOS 

-- Como verificar a versão do Git
```bash

git --version
```

-- Como criar uma pasta pelo git
```bash

mkdir nome_da_pasta
```

-- Como entrar na pasta criada
```bash

cd nome_da_pasta
```

-- Como listar os arquivos da minha pasta
```bash

ls
```

-- Como criar um arquivo sem conteudo na pasta. OBS:. pode ser qualquer formato, txt foi apenas um exemplo
```bash

touch nome_do_arquivo.txt
```

-- Quer criar um arquivo com conteúdo? 
```bash

echo "Contéudo dentro do arquivo" > nome_do_arquivo2.txt
```

-- Verificar se houve alguma modificação? OBS: aparecerá que arquivos foram criados, mas precisam ser adicionados
```bash

git status
```

-- Adicione o arquivo
```bash

git add nome_do_arquivo.txt
```

-- Realize o commit para ele entrar na branch
```bash

git commit -m "Descrição da acao/arquivo" nome_do_arquivo.txt
```

-- Quer confirmar se o arquivo está lá?
```bash

git log
```

-- Quer colocar o arquivo no repositório do github?
```bash

git push -f origin main
```
