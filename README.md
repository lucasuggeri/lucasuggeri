```JavaScript
const whoAmI = {
    name: 'Lucas Uggeri',
    yearsOld: 19,
    localization: 'Morro Reuter - RS - Brazil',
    languages: ['pt-BR','en-US'],
    occupation: 'Social media',
    hobby: ['Play video-games', 'sleep', 'watch animes'],
}
const tools = {
    frontEnd: ['HTML, CSS, JavaScript]
    backEnd: ['NodeJs','Pascal'],
    database: ['Firebird','SQLServer','PostgreSQL', 'MongoDb'],
    favoriteStack: ['MicroServices', 'Api', 'Telegram bot'],
}
const person = {
    ...whoAmI,
    knowledge: {
        ...tools
    }
}

module.exports = person



