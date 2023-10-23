# Twitter Bulk Follow Script

## Descrição
Este é um pequeno script Python que permite seguir várias contas do Twitter de uma só vez. Ele utiliza a biblioteca pyautogui pra simular o processo de abrir uma nova aba e seguir o perfil.

## Exemplo do script funcionando
![gif_do_script]('https://media.discordapp.net/attachments/723617049338970173/1166005465512149132/github_gif.gif?ex=6548ea36&is=65367536&hm=01770967203d88abccece238a0bc192385260e3db13de0946693231ae842392d&=&width=882&height=468')

## Requisitos
- Python 3.9
- Biblioteca pyautogui `pip install pyautogui`)
- Conta de desenvolvedor do Twitter com as chaves de acesso (API Key, API Secret Key, Access Token, Access Token Secret)

## Uso
1. Clone o repositório.
2. Instale as dependências necessárias usando `pip install pyautogui keyboard`.
3. Descubra as coordenadas do botão de seguir usando a função coordenadas() 
4. Edite a lista de contas que você deseja seguir no arquivo `twitter_profiles.py`.
5. Execute o script usando `python script.py`.