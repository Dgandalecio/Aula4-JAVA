/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.algoritmo348;

/**
 *
 * @author diogo
 */
import javax.swing.JOptionPane;
public class Algoritmo348 {

    public static void main(String[] args) {
       
        int L;
        
        Valores vetor= new Valores();
        
        for (L=0;L<=4;L++){
            
          
           String nome = JOptionPane.showInputDialog("Digite"+ (L+1) + "nome: ");
           vetor.nomes[L]=nome;
            
           //System.out.print(" Nome " + (L + 1) + ": " + vetor.nomes[L]+"" ); 
      
           String nota =JOptionPane.showInputDialog("Digite a 1 nota ");
           vetor.pr1[L]=Float.parseFloat(nota);
           
           // System.out.print(" Nota 1: "+vetor.pr1[L]+"");
            
            String nota2 =JOptionPane.showInputDialog("Digite a 2 nota ");
           vetor.pr2[L]=Float.parseFloat(nota2);
           
            //System.out.print(" Nota 2: "+vetor.pr2[L]+"\n");
            
            vetor.media[L]=(vetor.pr1[L] + vetor.pr2[L])/2;
            
            
            System.out.println("\n\n\n\t\t\t RELACAO FINAL\n");
           
        }
   for (L=0;L<=4;L++){
        
       System.out.print("\n -"+ vetor.nomes[L]);
        System.out.print(" \n "+ vetor.pr1[L] + vetor.pr2[L] + " \t "+ vetor.media[L]);
    }
}
}
