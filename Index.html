<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8 ">
  </head>
  <body>
<script>
importar  Phaser  desde  'phaser' ;
importar  logoImg  desde  './assets/logo.png' ;

class  MyGame  extiende  Phaser . Escena
{
    constructor  ( )
    {
        super ( ) ;
    }

    precarga  ( )
    {
        esto . cargar . imagen ( 'logo' ,  logoImg ) ;
    }
      
    crear  ( )
    {
        const  logo  =  esto . añadir . imagen ( 400 ,  150 ,  'logo' ) ;
        esto . preadolescentes . agregar ( {
            objetivos : logo ,
            y : 450 ,
            duración : 2000 ,
            facilidad : "Power2" ,
            yoyo : cierto ,
            bucle : - 1
        } ) ;
    }
}

const  config  =  {
    tipo : Phaser . AUTO ,
    padre : 'phaser-example' ,
    ancho : 800 ,
    altura : 600 ,
    escena : MyGame
} ;

 juego  constante =  nuevo  Phaser . Juego ( config ) ;
</script>

<script>
const merge = require("webpack-merge");
const path = require("path");
const base = require("./base");
const TerserPlugin = require("terser-webpack-plugin");

module.exports = merge(base, {
  mode: "production",
  output: {
    filename: "bundle.min.js"
  },
  devtool: false,
  performance: {
    maxEntrypointSize: 900000,
    maxAssetSize: 900000
  },
  optimization: {
    minimizer: [
      new TerserPlugin({
        terserOptions: {
          output: {
            comments: false
          }
        }
      })
    ]
  }
});
</script>
<script>
const webpack = require("webpack");
const path = require("path");
const HtmlWebpackPlugin = require("html-webpack-plugin");
const { CleanWebpackPlugin } = require("clean-webpack-plugin");

module.exports = {
  mode: "development",
  devtool: "eval-source-map",
  module: {
    rules: [
      {
        test: /\.js$/,
        exclude: /node_modules/,
        use: {
          loader: "babel-loader"
        }
      },
      {
        test: [/\.vert$/, /\.frag$/],
        use: "raw-loader"
      },
      {
        test: /\.(gif|png|jpe?g|svg|xml)$/i,
        use: "file-loader"
      }
    ]
  },
  plugins: [
    new CleanWebpackPlugin({
      root: path.resolve(__dirname, "../")
    }),
    new webpack.DefinePlugin({
      CANVAS_RENDERER: JSON.stringify(true),
      WEBGL_RENDERER: JSON.stringify(true)
    }),
    new HtmlWebpackPlugin({
      template: "./index.html"
    })
  ]
};
</script>

<script>

</script>
   </body>
       </html>
