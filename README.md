# Reconhecimento Facial com Anti-spoofing

#### Aluno: [Gabriel Taranto Pereira Magrina Ferreres](https://github.com/gabrieltp).
#### Orientador: [Felipe Borges](https://github.com/FelipeBorgesC).
#### Co-orientadora: [Ana Carolina Abreu](https://github.com/acarolina1612).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

O projeto consiste em um programa feito com redes pré-treinadas MTCNN para Reconhecimento Facial e utiliza também tecnologia anti spoofing, ou seja, torna o reconhecimento facial muito mais seguro e confiável através de controle contra ataque de fotos e vídeo. A pessoa reconhecida será somente validada quando o sistema identificar que não é uma foto ou vídeo da mesma. Isso é possível com detecção de coordenadas da pessoa e comparação em 2 dimensões. Logo, se a imagem detectada pela câmera tem 2 dimensões, será concluído que é um vídeo ou uma foto. Caso contrário, é uma pessoa realmente. Uma possível burlagem do sistema seria a utilização de máscaras com o rosto de alguém da base de dados, porém inseri uma detecção de 20 frames da mesma pessoa para validação, o que evita esse tipo de ataque também. Portanto, é um sistema bem seguro e funciona perfeitamente para entrada em qualquer ambiente que se queira. É importante ressaltar que alguns ajustes devem ser feitos caso exista muita luz ou muito pouca luz, pois alguns parâmetros devem ser configurados diferentemente dependendo do ambiente.

---

Matrícula: 191.477.022

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
