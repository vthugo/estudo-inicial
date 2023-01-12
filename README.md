# estudo-inicial


ls | lista\
cd | direciona\
mkdir | criar arquivo/pasta\
clear | limpeza\
rm |excluir arquivo/ pasta\
touch | gerar um arquivo vazio ou varios\
source | ler e executa um conteudo de um arquivo\
pwd | imprime o caminho do diretorio de trabalho\
nano | editor\
ssh-keygen | criar um par de chaves\
apt | instala pacotes de software\
  
## GIT 
clone | copiar um repositorio\
config| configurar repositorio\
add | adiciona uma alteração no diretório de trabalho à área de preparação\
status |  exibe o estado do diretório de trabalho e da área de preparação\
commit |  é usado para salvar suas alterações no repositório local\
push | empurra commit ate a nuvem\
git diff | mostra as alterações de um arquivo\


## FORMAS 

### SHEL

#### SE
```sh
if []; then
fi
```

#### SE/SENAO
```sh
if []; then
else
fi
```

##### FUNCTION
```sh
function nome_da_funcao () {
}
```

### JAVA

#### CLASSE
```java
package nome_do_caminho_das_pastas_ate_chegar_na_classe

public class nome_da_minha_classe{
}
```

##### FUNCTION MAIN
```java
public static void main (string[] args){
}
```

## INSTALAÇÃO

### JAVA

1. Baixar no site da oracle x64 Debian package
2. instalar pacote do java 
3. criar "JAVA_HOME" No  arquivo /home/vt/.bashrc
4. adicionar "JAVA_HOME" na PATH
5. confirmar instalação com: 
```sh
java --version
```

## RESUMO
### CONCEITOS BASICOS DE PROGAMAÇÃO
ex: loops,instruções if,variaveis e arrys

## 1º ATIVIDADE
* criar uma conta de avaliação no "oracle cloud"
* execultar o keygen para gerar chaves publicas e prividas
* provisionará a estancia de computação da vm com a imagem do do "oracle cloud" que tera um software
* configurar acesso de vnc
* conectar com a maquina virtual vnc
* baixar netbeans na maquina virtual e logo apos instalar
* define o jdk
* testa netbeans

### instruções binarias
* 1's e 0's e com que hardware execute codigo

### exemplos de progama c
#iclude < stdio.h >
int main (){
  print F ("hello, word!");
  return 0;
}

### JAVA: e uma linguagem de progamação de objetivo geral com uma 
sintaxe e uma estrutura semelhantes a "C e C++". criado originalmente na sun microsystems
en 1945
#### beneficios
* modularidade
* implenta a ocultação de informações
* facilita a reutilização do codigo
* capacidade de manutenção

##### objeto: um objeto pode usar outro objeto de diferentes formas e aplicações

##### class
* exemplo:
    public class custumer {
    	// feelds
    	// methods
    }

##### pacote java: e uma fora de organizar classe relacionadas ela representa a 
pasta na qual  classe sera salva.

* exemplo: 
package duke.choice;

  public class customer {
  // class body
  //fields und methods are
 placed here
  }

##### loops: e usados para execultar uma sequencia de instruções / funções
repetidamente quando algumas condições tornam-se true

##### variables: uma variavel refere-se a algo que pode ser alterado

##### Valores inteiros e duplos

* valores inteiros entre: 2,147,483,648
* valores positivos: 2,147,483,647
 * exemplos: 2,1343387,1_343_387

variaveis duplos manterão valores, maiores contendo partes decimais e poderão ser
numeros muito grandes ou pequenos

##### valores duplos

* exemplo: 987640059602230.7645,-1111, 2.1E12

##### constantes

* exemplo: 
      duplo salestax= 6.25;
salestax = 23.5;

final int NUMBER_OF_MONTHS =12;
NUMBER_OF_MONTHS =13; // não
sera compilado