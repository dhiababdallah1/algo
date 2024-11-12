#include<stdio.h>
#include<string.h>
#include<stdlib.h>

int main()
{
    printf("veuillez saisir la taille maximale de la chaine:\n");
    int N;
    scanf("%d",&N);
	char *p = malloc(N*sizeof(char));;
    char *ch = p;
    printf("%p\n",p);
    printf("%p\n",p+N);
	printf("donner le chaine de caractÃ©re: ");
		scanf("%c",p);
		p++;scanf("%c",p);
		p++;scanf("%c",p);
		p++;
	
    *(p + 1) = '\0';
    puts(ch);
    return 0;
}
 #include< stdio.h >
 #include< string.h >
 #include< stdlib.h >
 char *ChargerChaine(int N);
 int Longueur(char *ch);
 void InverserTab(char Tab[], char T[], int m);
 void ChargerTab(char *p, char Tab[]);
 void AfficherTab(char Tab[], int m);
 int main(){
 char *ch; int n; printf(”veuillez saisir la taille maximale de la chaine:\n”);
 scanf(”%d”,&n); ch=ChargerChaine(n);
 int m=Longueur(ch);
 char Tab[m], T[m];
 ChargerTab(ch,Tab);
 AfficherTab(Tab,m);
 InverserTab(Tab,T,m);
 AfficherTab(T,m);
 free(ch);
 return 0;
 }
