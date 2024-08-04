back-end

    install
        cd  back-end
        npm install -g yarn
        yarn install
        yarn --version

    RUN
        yarn serve

    DataBase
        back-end/src/plugins/mongoose.ts
        MongoBD 127.0.0.1:27017

front-end

    config your Phone IP
        fontend/src/apis/IP.js
        export const API_BASE_URL = 'http://192.168.43.8:3000/client-api'
                                                /\
                                                || Change This!
    install
        cd fontend
        npm install
        npm install @react-navigation/native
        npm install react-native-screens react-native-safe-area-context
        npm install axios

    RUN
        npm start

