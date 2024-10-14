# Projeto Star Schema - POWER BI
Desenhar processo Star Schema no POWER BI ⭐

## ⏳PROCESSO

- Foi utilizado o POWER BI para criar o modelo  - Star Schema.
- Foi criada as tabelas dimenssões denominadas por um D na frente
- Foi criado a tabela fato demoninada por um F na frete
- Todas as tabelas partindo de uma origem oculta
- Foi criado uma tabela dimensão D_Calendar (D_Calendario = CALENDARAUTO(12)) 
    -  Usado a Função CALENDARAUTO
- Foi criado grau de granularidade de mes e ano 
- Coluna mes criado com a função YEAR(Ano = YEAR('D_Calendario'[Date]))
- Coluna mes criado com a função FORMAT (Mes = FORMAT('D_Calendario'[Date],"mmmm", "en")) 
   - formatado em ingles para ter relação com tabela fato 



## 🛠️ FERRAMENTAS

[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=write)](https://docs.github.com/)
[![Vscode](https://img.shields.io/badge/Vscode-000?style=for-the-badge&logo=visual-studio-code&logoColor=blue)](https://code.visualstudio.com/)
[![MYSQL](https://img.shields.io/badge/MYSQL-000?style=for-the-badge&logo=MYSQL&logoColor=blue)](https://www.mysql.com/downloads/)
[![POWER BI](https://img.shields.io/badge/POWER%20BI%20-%20%23000000?style=for-the-badge&logo=POWER%20BI&logoColor=Balck&labelColor=Black)](https://www.microsoft.com/pt-br/power-platform/products/power-bi)


## 📚 REFERÊNCIAS

- [GIT. Documentation](https://git-scm.com/doc)
- [VSCODE. Download](https://code.visualstudio.com/)
- [VSCODE. Apender_usabilidade](https://code.visualstudio.com/learn)
- [VSCODE. Documentation](https://code.visualstudio.com/docs)
- [VSCODE. Atalhos_Keyboard](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
- [Visão Geral. Documentation](https://learn.microsoft.com/pt-br/power-bi/guidance/star-schema)
- [Documentation. dax](https://learn.microsoft.com/en-us/dax/)
- [Function Calendar. Calendarauto_dax](https://learn.microsoft.com/en-us/dax/calendarauto-function-dax)
- [Function Year. dax](https://learn.microsoft.com/en-us/dax/year-function-dax)
- [Function Format. dax](https://learn.microsoft.com/en-us/dax/format-function-dax)


## 📃 CERTIFICADO DE CONCLUSÃO
- [Criação do Modelo Star Schema - POWER BI](https://github.com/Car-Lopes/Projeto_DIO_PowerBI/tree/master/Desafio_6_Star_Schema_BI/Certificado)