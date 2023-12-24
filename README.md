# Zipping the Project

zip the folder

## Pushing the zip to the server:

push it to the server with `scp -r zipfolder.zip ssh:~/`

## Unzip the folder in the server

`unzip zipfolderfile.zip`

# Start a New Tmux session

`tmux new -s session_name`

# Attach to a Tmux session

`tmux a -t session_name`

# Allow people to access the port

`sudo ufw allow portname`

# Allow you to copy things from remote to server

`sudo chown -R username folder`
`sudo chmod 777 folder`

# Killing a Port
`fuser -k 8080/tcp`


# Add Sites enabled
`https://www.digitalocean.com/community/tutorials/how-to-set-up-nginx-server-blocks-virtual-hosts-on-ubuntu-16-04`

## Restart Nginx

`sudo systemctl restart nginx`

## Adding An SSL Certificate , we first add Certbort

`sudo add-apt-repository ppa:certbot/certbot`

`sudo apt-get update`

`sudo apt-get install python-certbot-nginx`

## Now we add the certificate

`sudo certbot --nginx -d example.com -d www.example.com`

## Asdf issues

https://stackoverflow.com/questions/72882383/how-do-i-recompile-rebar3-with-an-erlang-otp-25-compiler-running-elixir-1-13-4?rq=1


👤 **MICHAEL MUNAVU**

- GitHub: [@githubhandle](https://github.com/MICHAELMUNAVU83)
- Twitter: [@twitterhandle](https://twitter.com/MichaelTrance1)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/michael-munavu-78703a218/)
