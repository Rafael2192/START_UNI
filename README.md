# START_UNI
JAVA PROVA TÉCNICA

class Main 
{
    public static void main(String[] args) 
    {
        int entrada;
        entrada = 7;

        Scanner scanner = new Scanner(System.in);
        System.out.println("Informar um número: ");
        entrada = scanner.nextInt();

        int multiplicador = 5;
        while(multiplicador <= 10)
        {
            int resultado = entrada * multiplicador;
            System.out.println(resultado);   
            multiplicador++;
        }
        
        
    }
