# webpack4-starter
https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1


##A quick description of how rules usually work:
{
        test: /\.YOUR_FILE_EXTENSION$/,
        exclude: /SOMETHING THAT IS THAT EXTENSION BUT SHOULD NOT BE PROCESSED/,
        use: {
          loader: "loader for your file extension  or a group of loaders"
        }
}
