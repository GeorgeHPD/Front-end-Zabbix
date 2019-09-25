## <div align="center">PERSONALIZAÇÃO LOGO E BACKGROUND ZABBIX</div>

---
#### LOGO [***Zabbix 4.2***]

**OBS.: Antes de qualquer edição realize o backup dos arquivos blue-theme.css e dark-theme.css**

**1° Acesse o diretorio Styles do zabbix onde vai encontrar os arquivos .css**

```/usr/share/zabbix/assets/styles```

**2° Utilizando o editor de sua preferencia, edite o tema de sua preferencia no meu caso utilizei o dark-theme.css**

```nano dark-theme.css ```

**3° No editor NANO utilizando o atalho ctrl+w procure (114px) para encontrar o codigo abaixo**

```
.signin-logo {
margin: 0 auto;
margin-bottom: 21px;
width: 114px;
height: 30px;
background: url(../img/icon-sprite.svg) no-repeat 0 -864px; }
```

**4° Apague esse codigo ou comente utilizando (/*) no começo e no final (*/),  eu optei por comentar igual a imagem abaixo:**

![001](https://user-images.githubusercontent.com/47629745/65557220-d9e66c00-df08-11e9-8f7d-3d4c109563a9.png)

**5° Cole no lugar o abaixo do codigo anterio o seguinte codigo:**
```
.signin-logo {
margin: 0 auto;
margin-bottom: 21px;
height: 85px;
background: url(../img/signin-logo.png) no-repeat 0; }
```
**Ficando igual a imagem abaixo**

![002](https://user-images.githubusercontent.com/47629745/65557398-90e2e780-df09-11e9-8724-71aeb20cdf6b.png)

**6° Adcione seu logo no tamanho (280px x 85px) no diretorio img do zabbix com o seguinte nome (signin-logo.png)**
```
/usr/share/zabbix/assets/img
```
** LOGO ALTERADO COM SUCESSO **
---


---
#### BACKGROUND [***Zabbix 4.2***]

**OBS.: Antes de qualquer edição realize o backup dos arquivos blue-theme.css e dark-theme.css**

**1° Acesse o diretorio Styles do zabbix onde vai encontrar os arquivos .css**

```/usr/share/zabbix/assets/styles```

**2° Utilizando o editor de sua preferencia, edite o tema de sua preferencia no meu caso utilizei o dark-theme.css**

```nano dark-theme.css ```

**3° No editor NANO utilizando o atalho ctrl+w procure (background-color) para encontrar o codigo abaixo**

```
body {
  line-height: 1.4em;
  color: #f2f2f2;
  background-color: #0e1012;
  margin-bottom: 60px;
  min-width: 950px;
  font-family: Arial, Tahoma, Verdana, sans-serif;
  font-size: 75%; }
```

**4° Comente ou apague a linha abaixo que define a cor do background em css**
```
background-color: #0e1012;
```
**5° Abaixo da linha anterior coloque esse codigo abaixo**
```
 background:url("../img/login-zabbix.jpg");
```

**Ficando igual a imagem abaixo**

![003](https://user-images.githubusercontent.com/47629745/65561821-41f17e00-df1a-11e9-9914-d94b2e0d854f.png)

**6° Escolha seu background com uma resolução baseada em seu monitor e adcione no diretorio img do zabbix**

**Obs.: cuidado com o nome do arquivo de background, deixe igual ao codigo (login-zabbix.jpg)**

**Estou utilizando a resolução de 2560x1080 irei disponibilizar 3 backgrounds**

```
/usr/share/zabbix/assets/img
```
**BACKGROUND ALTERADO COM SUCESSO**
---

---
## **Preview Geral**


![0101](https://user-images.githubusercontent.com/47629745/65563807-381f4900-df21-11e9-9203-a9c11db631a6.png)






