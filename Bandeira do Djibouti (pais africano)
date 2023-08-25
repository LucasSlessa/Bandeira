#include <GL/gl.h>
#include <GL/glut.h>7
#include <GL/glu.h>
#include <cmath>



void retangulo1() {
    // Desenhar o retângulo verde abaixo
    glColor3f(0, 0.655, 0);  // Verde
    glBegin(GL_QUADS);
    glVertex2f(-0.8, -0.4);//baixo esquerda
    glColor3f(1, 0.655, 0);  // Verde
    glVertex2f(0.5, -0.4);//baixo direita
    glColor3f(1, 0.655, 1);  // Verde
    glVertex2f(0.5, 0);//cima direita
    glColor3f(1, 1, 0.7);  // Verde
    glVertex2f(-0.3, 0);//cima esquerda
    glEnd();


}
void retangulo2() {
    // Desenhar o retângulo AZUL acima
    
    glColor3f(0.135, 0.706, 0.735);  // AZUL
    glBegin(GL_QUADS);
    glVertex2f(-0.3, 0.0);//baixo esquerda
    glColor3f(1, 0, 0.78);  // Verde
	glVertex2f(0.5, 0.0);//baixo direita
    glColor3f(1, 8, 1);  // Verde
    glVertex2f(0.5, 0.4);//cima direita
    glColor3f(01, 1, 0);  // Verde
    glVertex2f(-0.8, 0.4);//cima esquerda
    glEnd();


}


void triangulobranco() {
    // Desenhar o retângulo verde acima
    
    glColor3f(1, 1, 1);  // branco
    glBegin(GL_TRIANGLES);
    glVertex2f(-0.8, 0.4);//p1
    glVertex2f(-0.2, 0);//p2
    glVertex2f(-0.8, -0.4);//p3
    glEnd();


}


void estrela1() {
   
    
    glColor3f(1,0 , 1);  // red
    glBegin(GL_TRIANGLES);
    glVertex2f(-0.633, 0.068);//p1
    glVertex2f(-0.58, -0.011);//p1
    glVertex2f(-0.523, 0.068);//p3
  
    glEnd();


}

void estrela2() {
    
    
    glColor3f(1,0 , 0);  // red
    glBegin(GL_TRIANGLES);
    glVertex2f(-0.536, 0.068);//p1
    glVertex2f(-0.59, 0.068);//p2
    glVertex2f(-0.614, -0.07);//p3
  
    glEnd();


}

void estrela3() {
    
    
    glColor3f(1,0 , 0);  // red
    glBegin(GL_TRIANGLES);
    glVertex2f(-0.578 ,0.15);//p1
    glColor3f(1,0.5 , 1);  // red
    glVertex2f(-0.60, 0.03);//p2
    glColor3f(1,0 , 1);  // red
    glVertex2f(-0.54, -0.07);//p3
  
    glEnd();


}
void display() {
    glClear(GL_COLOR_BUFFER_BIT);
    glLoadIdentity();

    retangulo1();
    retangulo2();
	triangulobranco();
	estrela1();
	estrela2();
	estrela3();
	
    glutSwapBuffers();
}

int main(int argc, char** argv) {
    glutInit(&argc, argv);
    glutInitDisplayMode(GLUT_RGBA | GLUT_DOUBLE);
    glutInitWindowSize(800, 600);
    glutCreateWindow("Bandeira do Djibouti");
    glutDisplayFunc(display);
    glutMainLoop();
    return 0;
}
