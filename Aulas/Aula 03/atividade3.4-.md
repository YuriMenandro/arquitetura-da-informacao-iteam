# Atividade Prática

Nome: Yuri Gabriel Porto Corrêa 

GitHub: https://github.com/YuriMenandro

E-mail: iuriporto648@gmail.com

1. Auditoria de Rotulagem. Identificar rótulos confusos em um aplicativo governamental e propor uma nova taxonomia de nomes.
2. Dado um menu confuso -> melhorar os rótulos

# Site escolhido: ITEAM
URL: https://www.iteam.org.br/

O Instituto Tecnológico Educacional do Amazonas (ITEAM), embora não se trate de uma aplicação governamental, atua em parceria com prefeituras e órgãos governamentais para oferecer capacitações profissionais e projetos de tecnologia.



# Sistemas de Organização identificados:


### Organização por tópico
```
Ex: Em Áreas de Atuação e Menu.
```
### Organização cronológica
```
Ex: Em novidades do ITEAM.
```

A ordenação cronológica é inconsistente, quando se analisa no preview da página inicial os itens aparecem do mais recente para o mais antigo (2024 a 2022), mas na página interna "Novidades"
acessada pelo menu, a ordem se inverte, exibindo do mais antigo para o mais recente (2022 a 2024).


Dentro do site, há um problema estrutural em "Educação Empresarial" e "Cursos". Educação Empresarial aparece no mesmo nível que Cursos, o que faz parecer que são independentes, mas ao navegar pelos conteúdos
verifica-se que os mesmos cursos listados em Educação Empresarial também aparecem dentro de Cursos/Capacitação. Isso evidencia que essa separação não segue um critério consistente, e sim uma 
duplicação de conteúdo para rótulos diferentes. Além disso, a organização por tarefa é quase ausente no site, sendo "Enviar mensagem" e 
"Voltar para a página principal", duas das poucas identificadas.

# Ética e Acessibilidade

### Acessibilidade:
```
 O site não apresenta suporte a LIBRAS nem indícios de compatibilidade com leitores de tela, algumas imagens sem descrição e não permite acessar muita coisa apenas com o teclado.
```
### LGPD
```
Existe o formulário na seção de "Fale Conosco" em que solicita nome, telefone, e-mail e mensagem sem indicar como esses dados
serão usados ou armazenados, e não há aviso de consentimento de cookies. O site possui políticas institucionais acessíveis pelo
menu (como Código de Ética e de Conduta, Política de Compliance e Política de Qualidade), porém nenhuma delas corresponde a uma
Política de Privacidade específica sobre o tratamento de dados coletados no site.
```

# Rótulos


Ainda abordando os problemas do sistema ITEAM, embora aparente ser funcional à primeira vista, após uma análise é perceptível que existem falhas que são identificáveis em poucos minutos de navegação.


### "Cursos - CAPDA/SUFRAMA"
```
Usa siglas técnicas que só fazem sentido para quem já conhece o programa, um usuário comum não irá saber o que significa essas siglas.
```

### "Novidades"
```
Novidades acaba sendo um termo muito genérico e a seção está desatualizada. Contém editais antigos e a última atualização foi em 2024.
```

# Proposta de Taxonomia

**"Cursos - CAPDA/SUFRAMA" → "Cursos"**
```
Remove a sigla técnica do rótulo, mantendo a informação dos programas dentro da própria página.
```
**"Novidades" → "Editais"**
```
Nomeia o conteúdo pelo que ele realmente demonstra ser e corrige o termo genérico.
```

Manter "Educação Empresarial" como uma página informativa e de apresentação, removendo a listagem dos cursos. A página passaria a ter uma ação de tarefa, como "Confira nossos cursos de 
Capacitação", direcionando o usuário para a listagem única em Cursos/Capacitação. Isso resolve a duplicação do mesmo conteúdo em páginas diferentes e introduz mais uma organização por
tarefa, deixando mais dinâmica a experiência do usuário.

