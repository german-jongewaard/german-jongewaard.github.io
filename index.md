## Welcome to Jongewaard GitHub Pages

Page in construction.
![Image of Yaktocat](https://german-jongewaard.github.com/constru.gif) 

If you want to contact me, _write me to the email_: germanjongewaard@gmail.com

You also can use the [editor on GitHub](https://github.com/german-jongewaard/german-jongewaard.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
public class Uso_Empleado {
 
    public static void main(String[] args) {
       
        Jefatura jefe_RRHH = new Jefatura("Juan", 55000, 2006, 9, 25);
        
        jefe_RRHH.estableceIncentivo(2570);
        
        Empleado[] misEmpleados = new Empleado[5];
        
        misEmpleados[0] = new Empleado("Ana", 30000, 2000, 07, 07);
        misEmpleados[1] = new Empleado("Carlos", 50000, 1995, 06, 15);
        misEmpleados[2] = new Empleado("Paco", 25000, 2005, 9, 25);
        misEmpleados[3] = new Empleado("Antonio", 47500, 2009, 11, 9);
        misEmpleados[4] = jefe_RRHH; /*Polimorfismo en acción, 
                                       principio de sustitución*/
         
        //EJEMPLO CON EL FOR EACH (FOR MEJORADO) :-)
        for(Empleado e: misEmpleados){
            /*Aumento el sueldo de los empleados un 5% */
            e.subeSueldo(5);
        }
        for(Empleado e: misEmpleados){
            System.out.println("Nombre: " + e.dameNombre() + 
                " Sueldo: " + e.dameSueldo() + " Fecha de alta: " +
                e.dameFechaContrato()); 
        }        
    }    
}

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/german-jongewaard/german-jongewaard.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
