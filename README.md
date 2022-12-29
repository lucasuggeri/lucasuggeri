```JavaScript
const whoAmI = {
    name: 'Lucas Uggeri',
    yearsOld: 19,
    localization: 'Estância Velha - RS - Brazil',
    languages: ['pt-BR','en-US'],
    occupation: 'Operador de loja',
    hobby: ['Play video-games', 'sleep'],
}
const tools = {
    frontEnd: ['HTML, CSS, JavaScript]
    backEnd: ['NodeJs','Pascal'],
    database: ['Firebird','SQLServer','PostgreSQL', 'MongoDb'],
    favoriteStack: ['MicroServices', 'Api'],
}
const person = {
    ...whoAmI,
    knowledge: {
        ...tools
    }
}

module.exports = person



