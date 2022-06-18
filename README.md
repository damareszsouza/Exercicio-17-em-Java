# Exercicio-17-em-Java
Como converter Strings para inteiros - Replica do exercicio do livro Tutorial em Java

Como converter Strings para inteiros:
Se você inserir o seguinte método na nossa classe ReadString, poderá ler valores inteiros do
teclado.
static int leInteiro() {
 
 String line;
 
 DataInputStream in = new DataInputStream(System.in);
 try {
 line = in.readLine();
 int i = Integer.valueOf(line).intValue();
 return i;
 }
 catch (Exception e) {
 return -1;
 }
 
 }
