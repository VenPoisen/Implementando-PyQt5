# Implementando-PyQt5
### Implementando PyQt5 em um código antigo de gerador e validador de CPF
#### Descrição dos arquivos:
- A interface foi criada no Qt Designer e importada no formato design.ui;
- O arquivo interface.py é a conversão da interface criada (design.ui) usando o seguinte código no terminal: ´´´pyuic5 design.ui -o interface.py´´´;
- Os arquivos gerador_cpf.py e validacpf_resolucao.py são scripts criados para gerar um cpf e validar um cpf, respectivamente;
- O arquivo app.py é onde se encontra o código principal que conecta o gerador e o validador com a interface criada;
