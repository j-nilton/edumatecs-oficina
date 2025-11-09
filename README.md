# Modelo de Artigo Acadêmico em LaTeX

## Sobre o Modelo
Este modelo em **LaTeX** foi desenvolvido para a elaboração de **artigos científicos**, conforme as normas da **ABNT NBR 6022:2018**, seguindo a estrutura adotada pelo **Instituto Federal de Educação, Ciência e Tecnologia do Piauí (IFPI)**.  

O sistema de **referências bibliográficas** baseia-se no pacote [**abnTeX2**](http://www.abntex.net.br/) e inclui comandos personalizados que facilitam o preenchimento de informações institucionais, autoria e orientações.  

Recomenda-se o uso do compilador **pdfLaTeX (versão 2024)** para garantir compatibilidade e correta geração do PDF.

---

## Estrutura do Projeto
O modelo já vem com a estrutura básica de um artigo científico:
- **Capa e contracapa automáticas**  
- **Resumo e Abstract** com palavras-chave  
- **Seções padrão**: Introdução, Referencial Teórico, Metodologia, Resultados, Conclusões  
- **Ambientes personalizados**:
  - `figuraCustom` → Inserção de figuras com legenda e fonte  
  - `tabelaCustom` → Criação de tabelas padronizadas  
  - `quadroCustom` → Quadros diferenciados da contagem de tabelas  
  - `citacaodireta` e `citacaoCodigo` → Citações textuais e de código  
  - `apendice` e `anexo` → Inclusão de materiais complementares  

---

## Como Usar
1. **Preencha os campos de identificação:**
   ```latex
   \titulo{Título do Artigo}
   \autor{Nome Completo}
   \instituicao{Instituto Federal do Piauí}
   \campus{Campus Piripiri}
   \curso{Tecnólogo em Análise e Desenvolvimento de Sistemas}
   \ano{2025}
   \orientador{Prof. Dr. Nome do Orientador}
   ```
   
2. Adicione o conteúdo nas **seções existentes**.  
3. Compile o documento utilizando o **pdfLaTeX**.

---

## Referências

**Manual institucional:**  
[Manual de Trabalhos Acadêmicos do IFPI](https://www.ifpi.edu.br/area-do-estudante/bibliotecas/manual-de-trabalhos-academicos)

**Base LaTeX:**  
[abnTeX2 – Modelo ABNT para LaTeX](http://www.abntex.net.br/)

---

## Autor

**José Nilton Silva Lima**  
📄 [Currículo Lattes](https://lattes.cnpq.br/9910161133761662)

---

## Licença

© 2025 **José Nilton Silva Lima**. Todos os direitos reservados.  
É permitida a cópia, distribuição e modificação **para fins acadêmicos**, desde que mantidos os créditos originais.  
**Uso comercial proibido** sem autorização prévia do autor.

