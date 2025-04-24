# ProjetoForms1.FrmMetodos
Formulario contendo os métodos referente aos cálculos do FrmMetodos.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Xml.Schema;

namespace ProjetoForms1
{
    public class Operacoes
    {
        //Esta classe vai conter os métodos referente aos cálculos do FrmMetodos

  //Métodos da Calculadora
        //Somar
        public int Somar(int x, int y)
        {
            int total = x + y;
            return total;
        }
        //Subtrair
        public int Subtrair(int v1,int v2)
        {
            int total = v1 - v2;
            return total;
        }
        //Multiplicar
        public int Multiplicar(int val1,int val2)
        {
            int total = val1 * val2;
            return total;
        }
        //Dividir
        public int Dividir(int valor1,int valor2)
        {
            int total = valor1 / valor2;
            return total;
        }

  //Método do Par ou Ímpar
        public int ParImpar(int numero)
        {
            if (numero%2 == 0)
            {
                return 0;
            }
            else
            {
                return 1;
            }

  }

  //Método da Média Aritmética
        public double MediaAritmetica(double n1,double n2,double n3) 
        {
            double total = (n1 + n2 + n3) / 3;
            return total;
        }

  //Método do Múltiplos de 7
        public int Multiplos(int numero)
        {
            if (numero % 7 == 0)
            {
                return 0;
            }
            else
            {
                return 1;
            }

  }

}
}
