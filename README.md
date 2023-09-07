# aula-013
joaoth1720
//this is a js file
//joao arthur

const professor = {
    nome: 'Vitor',
    idade: 27,
    email: 'vitor@gmail.com'
}

console.log(professor.idade);
console.log(professor["email"]);

professor.nome = 'Mika'
professor['email'] = 'profmika@gmail.com'

const filme = {
    filme: 'vovozona',
    direçao: 'Raja Gosnell',
    anolança: 2000,
    elenco: ["sherry pierce", "martin lawrence"],
    javiu:Boolean(true)
}

console.log(filme.filme);
console.log(filme.direçao);
console.log(filme.anolança);
console.log(filme.elenco);
console.log(filme.javiu);


 filme.vovozona = 'pikachu'
 filme['javiu'] = 'false'


 const pessoa = {
    nome:'thiago',
    idade: 19,
    genemusifav:'pagode,funk,trap'

 }

 console.log('o nome da e '+ pessoa.nome+'ela tem '+pessoa.idade+'anos e gosta muito de'+pessoa.genemusifav) 

const donoDopet = {
    nome: "vitor hugo",
    pet: {
        nomeDopet: "wanda",
        raca: "vira-lata",
        idade: 1 

    }
}
console.log(donoDopet.pet.momeDopet);

const curso = {
    nome: "Noturno Frontend",
    linguagens: ["js", "css", "HTML"]
}
console.log(curso.linguagens[0]);

const professores = [
    {nome: "Andrei", madulo: 1},
    {nome: "Vitor", madulo: 2},
    {nome: "Mina", modulo: 3}
]
console.log(professores[1].nome);

//Notação de ponto: curso.numeroEstudantes = 50
//Notação de colchetes: curso['numeroEstudantes'] = 50

filme.personagens = ["trent", "malcolm"];
console.log(" o personagem " + filme.personagens[0] + " e interpretado por " + filme.elenco[0] + " e o personagem " + filme.personagens[1] + " e interpretado por " + filme.elenco);

filme.elenco[0] = "xuxa"
console.log(filme);

const usoario = {
    nome: 'prof' ,
    idade: 25,
    email: 'prof@senacrs.com.br' ,
    cidade: ' sao paulo'
}

const novoUsoario = {
    ...usoario,
    nome: 'joao' ,
    idade: 28
}

const listaDeNomes = ["Mika", "paula", "vitor"]

const copiaListaDeNomes = [...listaDeNomes]
copiaListaDeNomes[0] = "vitor"
console.log(copiaListaDeNomes);


const copiaPessoa = {
    ...pessoa,
    comidaFav: ["pizza", "pastel", "feijao", "panquecas"],
    melhorAmigo: {
        nome: "pedro",
        idadeAmigo: 16,
    }
}

console.log(" o nome da pessoa e " + pessoa.nomePessoa + " e suas comidas preferidas sao: " + copiaPessoa.comidaFav + ". seu melhor amigo se chama " + copiaPessoa.melhorAmigo.nome + " e tem " + copiaPessoa.melhorAmigo.idadeAmigo + " anos ");
