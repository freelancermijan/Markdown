git add . &&  git commit -m "File Updated" && git push -u origin main

## This Repo all about tools installation & commands

<details>
  <summary> wpscan </summary>

  <blockquote>

  <details>

  <summary> installation </summary>
  
  <blockquote>

  ```
  sudo apt install build-essential libcurl4-openssl-dev libxml2 libxml2-dev libxslt1-dev ruby-dev -y && sudo apt install ruby-full -y && sudo gem install wpscan
  ```

  </blockquote></details>

  <details><summary> Usage </summary><blockquote>

  Vulnerable theme, plugin, users
  ```
  sudo wpscan --url "https://wordpress.org" --random-user-agent --enumerate vp,vt,u -t 5 -o wordpress.org.wpscan.txt
  ```
  </blockquote></details>

  </blockquote>

</details>