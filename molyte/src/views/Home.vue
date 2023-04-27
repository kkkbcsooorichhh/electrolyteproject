<template>
  <div>
    <div class="text-description">
                    <p class="p-title">
                        Molyte电解液数据库
                    </p>
                    <p class="p-content">
                        Molyte是一款专注于电解液材料设计与数据挖掘的自主研发知识库。运用计算材料学方法，收集数百万种有机溶剂分子和电解液结构数据，以支持高性能电解液材料设计和研发。</p>
                    <img src="../assets/eProjectOutlineP1.png" alt="">
                    </div>
                <div class="text-description">
                    <p class="p-title">
                        Molyte电解液数据库
                    </p>
                    <p class="p-content">
                        有机溶剂分子数据模块：该模块包含数百万种有机溶剂分子的物理性质、电荷布居、静电势分布，离子结合能以及其他相关的物理性质数据。这些数据为电解液材料设计和发现提供了关键信息，可用于快速筛选和优化有机溶剂分子的性质和特征，以满足电解液应用的要求。</p>
                    <img src="../assets/eProjectOutlineP2.png" alt="">
                    </div>
                <div class="text-description">
                    <p class="p-title">
                        Molyte电解液数据库
                    </p>
                    <p class="p-content">
                        电解液结构数据模块：该模块包含了电解液中阳离子径向分布函数、配位数、溶剂化第一鞘层结构以及溶剂结构分布等重要结构参数数据。这些数据可以用于理解电解液的结构和性质，帮助开发新型的高性能电解液，进一步推动快充和低温电池的设计和开发。</p>
                    <img src="../assets/eProjectOutlineP3.png" alt="">
                    </div>
                <div class="text-description">
                    <p class="p-title">
                        Molyte电解液数据库
                    </p>
                    <p class="p-content">
                        数据驱动的机器学习模块：该模块利用有机溶剂分子数据和电解液结构数据，采用数据驱动的方法来开发新型的电解液。通过机器学习算法的训练和优化，可以快速预测电解液的性质和特性，并优化电解液组分的比例和配方，以满足不同应用场景下的要求。</p>
                </div>
  </div>
</template>

<style>
.text-description {
	width: 28rem;
	position: relative;
	left: 50%;
	-webkit-transform: translate(-50%);
	transform: translate(-50%);
	text-align: center;
	border-bottom: 1px solid #141379;
	padding-bottom: 0.65rem;
	border-bottom: 0.025rem solid #141379;
}
.text-description p {
	text-align: center;
	width: 28rem;
}
.eProjectOutline .text-description img {
	width: 100%;
}

.p-title {
	height: 0.5rem;
	padding-top: 1.25rem;
	font-size: 0.6rem;
	line-height: 0.75rem;
}

.p-content {
	font-size: 0.4rem;
	line-height: 0.75rem;
}
</style>
