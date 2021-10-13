    package app;
    
	import javax.swing.JOptionPane;	

	import Classes.Aluno;
    import Classes.Despesas;

	public class UI {
		
		public static void main(String[] args) {
			
			int op;
			do { 

				String strOpcao = JOptionPane.showInputDialog("Selecione uma opcao : \n"
						+ "1 - Cadastro de pessoas\n"
						+ "2 - Cadastro de despesas\n"
						+ "3 - Cadastro de categorias\n"
						+ "0 - Sair do programa");
				op = Integer.parseInt(strOpcao);

				switch (op) {
				case 1:
                //criação de aluno
					break;

				case 2:
                //criação de despesa
					break;

				case 3: 
                //criação de categoria
					break;

				case 0: 
					//sair do programa
					break;

				default:
					JOptionPane.showInputDialog("ERRO\n");
					break;
				}
			} while (opcao != 0);
