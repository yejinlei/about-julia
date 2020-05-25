# about-Julia

## 安装环境
1. 下载 [julia-1.4.2-win64.exe](https://share.weiyun.com/NC5mUNzw)、[JuliaPro_v1.4.1-1_build-274.exe](https://share.weiyun.com/K6cVQL8p)
2. 添加国内镜像

    using Pkg
    
	Pkg.add("PkgMirrors")
    
	using PkgMirrors
    
	PkgMirrors.setmirror("ZJU")

3. 安装常用包

    using Pkg

    Pkg.add("Plots")

    Pkg.add("IJulia")

    Pkg.add("Images")

    Pkg.add("ImageView")

    Pkg.add("ImageMagick")

    Pkg.add("Distributions")

    Pkg.add("Distances")

    Pkg.add("DataFrames")

    Pkg.add("CSV")

    Pkg.add("JSON")

    Pkg.add("Gadfly")

    Pkg.add("ECharts")

    Pkg.add("VegaLite")

    Pkg.add("TensorFlow")

    Pkg.add("Flux")

    Pkg.add("ScikitLearn")

    Pkg.add("DecisionTree")

    Pkg.add("Boltzmann")

    Pkg.add("BayesNets")

    Pkg.add("HDF5")

    using Images,IJulia,ImageView,ImageMagick

    using Plots,Distributions,Distances,DataFrames

    using CSV,JSON,Gadfly,ECharts,VegaLite

    using TensorFlow,Flux,ScikitLearn

    using DecisionTree,Boltzmann,BayesNets
