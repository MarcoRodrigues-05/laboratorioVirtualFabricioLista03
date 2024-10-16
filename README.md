# laboratorioVirtualFabricioLista03

atividade 01

atividade 02

        System.out.println("Agora o seu peso: ");
        peso01 = entrada.nextDouble();
        System.out.println("Digite a segunda nota: ");
        nota02 = entrada.nextDouble();
        System.out.println("Agora o seu peso: ");
        peso02 = entrada.nextDouble();
        System.out.println("Digite a terceira nota: ");
        nota03 = entrada.nextDouble();
        System.out.println("Agora o seu peso: ");
        peso03 = entrada.nextDouble();
        
        mediaPonderada = (nota01 * peso01)+(nota02 * peso02)+(nota03 * peso03)/ nota01+nota02+nota03;
        
        System.out.println("A média ponderada é: " + mediaPonderada);
                       
      }else if(menu == 3){
        System.out.println("Saindo...");
      }else{
        System.out.println("Opção inválida!");
      }
    }
    
    
    
  }
}
