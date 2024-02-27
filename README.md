# **GIT BRANCHS**

## **Cria a branch localmente**
                                                                
    git branch <branch_name>
    git branch <child_branch> <mother_branch>
  
**ou**

    git checkout -b <branch_name>

## **Listar branches**

    git branch -a

## **Verificar branch atual**

    git status

## **Atualizando branch**

    git branch -m <branch_name> <new_branch_name>

## **Cria a branch no remoto**

    git push -u origin <HEAD_branch> <new_branch>  	//OBS: A nova branch herda todo o conteúdo da HEAD_branch

## **Trocar a branch**

    git switch <branch_name> //especifico para trocar de branchs

**ou**

    git checkout <branch_name> //faz diversas funções como excluir branchs, etc

## **Remover branch local**

    git branch -d <branch_name> //Não deleta a branch remota
	
## **Remover branch do remoto**

    git push origin <HEAD_branch> -d <branch_name> //Não deleta a branch local
	
## **Merge de branches**

    git merge <branch_name> //Primeiramente deve ser feito o switch para a branch que vai receber o merge
	
    git push 

**ou**

    git push origin <branch_name>
