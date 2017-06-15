## shintech-mysql

### Synopsis

Initialize mysql

### Installation

    yarn install shintech-mysql
    
### Usage

    import init from 'shintech-mysql'
    
    const options = {
      environment: process.env['NODE_ENV'],
      logger: winston,
      config: config
    }
    
    const db = init(options)