```JavaScript
const whoAmI = {
    name: 'Lucas Uggeri',
    yearsOld: 19,
    localization: 'Estância Velha - RS - Brazil',
    languages: ['pt-BR','en-US'],
    occupation: 'Operador de loja',
    hobby: ['Play RPG', 'video games'],
}
const tools = {
    backEnd: ['NodeJs','Pascal'],
    database: ['Firebird','SQL Server','PostgreSQL', 'MongoDb'],
    favoriteStack: ['MicroServices', 'Api'],
}
const person = {
    ...whoAmI,
    knowledge: {
        ...tools
    }
}

module.exports = person```



