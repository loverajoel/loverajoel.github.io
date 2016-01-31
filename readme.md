```javascript
var me = {
	name: 'Joel',
	lastname: 'Lovera',
	nationality: 'Argentina'
};

var currentPosition = {
	company: 'Olapic',
	url: 'https://www.olapic.com',
	role: 'Javascript Developer'
};

var profiles = {
	github: 'https://github.com/loverajoel',
	twitter: 'https://twitter.com/loverajoel',
	angellist: 'https://angel.co/joel-lovera'
};

var blog = 'https://jstips.co';

// Latest open source projects
var openSource = [
	{
		name: 'spotify-sdk',
		repository: 'https://github.com/loverajoel/spotify-sdk',
		roles: ['autor'],
		tags: ['js', 'es6']
	},
	{
		name: 'MagicPlaylist',
		url: 'http://magicplaylist.co',
		repository: 'https://github.com/loverajoel/magicplaylist',
		roles: ['autor'],
		tags: ['js', 'es6', 'music', 'spotify']
	},
	{
		name: 'timeance.js',
		repository: 'https://github.com/loverajoel/timeance.js',
		roles: ['autor'],
		tags: ['js', 'performance']
	},
	{
		name: 'sqlalchemy-elasticquery',
		repository: 'https://github.com/loverajoel/sqlalchemy-elasticquery',
		roles: ['autor'],
		tags: ['python', 'sqlalchemy']
	}
];

Object.assign({}, me, profiles, {currentPosition}, {blog}, {openSource})

```