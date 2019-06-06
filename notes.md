const  crypto = require('crypto-extra)

crypto.hash('hello world', { algorithm: 'sha256' })

Can hash a hash over and over to prevent rainbow tables


///

const bcrypt = require('bcrypt')

// will hash hello world 2^10
bcrypt.hashSync('hello world', 10);

// will hash hello world 2^16
bcrypt.hashSync('hello world', 16);

// Everytime hashing with bcrypt will give a new random string.
