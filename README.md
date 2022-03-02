# VideoQA

# Video Question Answering: Datasets, Algorithms and Challenges

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

This repository contains a list of papers, codes, datasets, leaderboards of Video Question Answering (VideoQA). If you found any error, please don't hesitate to open an issue or pull request.

If you find this repository helpful for your work,  please kindly cite the following paper. The Bibtex are listed below:
<pre>
@article{zhong2022Video,
      title={Video Question Answering: Datasets, Algorithms and Challenges}, 
      author={Yaoyao Zhong and Wei Ji and Junbin Xiao and Yicong Li and Weihong Deng and Tat-Seng Chua},
      year={2022},
      article={arXiv},
}
</pre>

## Contributor

Contributed by [Yaoyao Zhong](https://zhongyy.github.io) and [Wei Ji]().

Thanks for supports from our adviser [Tat-Seng Chua](https://www.chuatatseng.com/)!

## Resources

### Open-sourced code
### Datasets

<div style="overflow-x: auto; overflow-y: auto; height: auto; width:100%;">
<table style="width:100%" border="2">
<thead>
  <tr>
    <th>Name</th>
    <th>Links</th>
    <th>Types</th>
    <th>Source</th>
    <th>#Video/#Qustion/Video Length(s)</th>
    <th>Annotation</th>
  </tr>
</thead>

<tbody>
	<tr>
	<td><code>VideoQA(FIB)</code></td>
		<td><a href="https://arxiv.org/pdf/1511.04670.pdf">[Paper]</a>,
            <a href="https://github.com/ffmpbgrnn/VideoQA">[Dataset]</a></td>
		<td> VideoQA, Factoid </td>
		<td> Multiple source </td>
		<td> 109K/390K/-  </td>
		<td> Auto</td>
	</tr>
	<tr>
	<td><code>VideoQA</code></td>
		<td><a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14906/14319">[Paper]</a>,
            <a href="http://aliensunmin.github.io/project/video-language/">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Web videos</td>
		<td> 18K/174K/90</td>
		<td> Auto, Man</td>
	</tr>	
	<tr>
	<td><code>MovieQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Tapaswi_MovieQA_Understanding_Stories_CVPR_2016_paper.pdf">[Paper]</a>,
            	<a href="http://movieqa.cs.toronto.edu/home/">[Dataset]</a>,
		<a href="https://github.com/makarandtapaswi/MovieQA_CVPR2016/">[Code]</a></td>
		<td> MM VideoQA, Factoid </td>
		<td> Movie </td>
		<td> 6.7K/6.4K/202  </td>
		<td> Man</td>
	</tr>
	<tr>
	<td><code>TGIF-QA</code></td>
		<td><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Jang_TGIF-QA_Toward_Spatio-Temporal_CVPR_2017_paper.pdf">[Paper]</a>,
            <a href="https://github.com/YunseokJANG/tgif-qa">[Dataset]</a></td>
		<td> VideoQA, Factoid </td>
		<td> GIF </td>
		<td> 71K/165K/3  </td>
		<td> Auto, Man</td>
	</tr>
	<tr>
	<td><code>MovieFIB</code></td>
		<td><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Maharaj_A_Dataset_and_CVPR_2017_paper.pdf">[Paper]</a>,
            	<a href="https://sites.google.com/site/describingmovies/home">[Dataset]</a>,
		<a href="https://github.com/teganmaharaj/movieFIB">[Code]</a></td>
		<td> MM VideoQA, Factoid </td>
		<td> Movie </td>
		<td> 118K/348K/4.1</td>
		<td> Auto</td>
	</tr>	
	<tr>
	<td><code>MSVD-QA</code></td>
		<td><a href="http://staff.ustc.edu.cn/~hexn/papers/mm17-videoQA.pdf">[Paper]</a>,
            <a href="https://github.com/xudejing/video-question-answering">[Dataset]</a></td>
		<td> VideoQA, Factoid </td>
		<td> MSVD </td>
		<td> 1.9K/50K/10</td>
		<td> Auto</td>
	</tr>	
	<tr>
	<td><code>MSRVTT-QA</code></td>
		<td><a href="http://staff.ustc.edu.cn/~hexn/papers/mm17-videoQA.pdf">[Paper]</a>,
            <a href="https://github.com/xudejing/video-question-answering">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> MSR-VTT</td>
		<td> 10K/243K/15</td>
		<td> Auto</td>
	</tr>	
	<tr>
	<td><code>YouTube2Text-QA</code></td>
		<td><a href="https://arxiv.org/pdf/1707.06355.pdf">[Paper]</a></td>
		<td> VideoQA, Factoid </td>
		<td> MSVD </td>
		<td> 1.9K/48K/-</td>
		<td> Auto</td>
	</tr>	
	<tr>
	<td><code>MarioQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Mun_MarioQA_Answering_Questions_ICCV_2017_paper.pdf">[Paper]</a>,
            	<a href="https://cvlab.postech.ac.kr/research/MarioQA/">[Dataset]</a>,
		<a href="https://github.com/JonghwanMun/MarioQA">[Code]</a></td>
		<td>MM VideoQA, Factoid</td>
		<td> Gameplay</td>
		<td>92K/92K/3-6 </td>
		<td> Auto</td>
	</tr>	
	<tr>
	<td><code>PororoQA</code></td>
		<td><a href="https://www.ijcai.org/Proceedings/2017/0280.pdf">[Paper]</a>,
            <a href="https://github.com/Kyung-Min/PororoQA">[Dataset]</a>,
		<a href="https://github.com/Kyung-Min/Deep-Embedded-Memory-Networks">[Code]</a></td>
		<td> MM VideoQA, Factoid</td>
		<td> Cartoon </td>
		<td> 171/8.9K/8.3</td>
		<td> Man</td>
	</tr>	
	<tr>
	<td><code>TVQA</code></td>
		<td><a href="https://aclanthology.org/D18-1167.pdf">[Paper]</a>,
           	<a href="http://tvqa.cs.unc.edu/">[Dataset]</a>,
		<a href="https://github.com/jayleicn/TVQAplus">[Code]</a></td>
		<td>MM VideoQA, Factoid</td>
		<td>TV</td>
		<td>21K/152K/76</td>
		<td>Man</td>
	</tr>	
	<tr>
	<td><code>SVQA</code></td>
		<td><a href="https://dl.acm.org/doi/abs/10.1145/3240508.3240563">[Paper]</a>,
            	<a href="https://svqa-founder.github.io/SVQA/">[Dataset]</a>,
		<a href="https://github.com/SVQA-founder/SVQA/tree/master/code">[Code]</a></td>
		<td> VideoQA, Factoid </td>
		<td> Unity3D </td>
		<td> 12K/118K/- </td>
		<td> Auto </td>
	</tr>	
	<tr>
	<td><code>Social-IQ</code></td>
		<td><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zadeh_Social-IQ_A_Question_Answering_Benchmark_for_Artificial_Social_Intelligence_CVPR_2019_paper.pdf">[Paper]</a>,
            <a href="https://github.com/A2Zadeh/Social-IQ">[Dataset]</a></td>
		<td> MM VideoQA, Inference</td>
		<td> Web Videos</td>
		<td> 1.2K/7.5K/-</td>
		<td> Man</td>
	</tr>	
	<tr>
	<td><code>ActivityNet-QA</code></td>
		<td><a href="https://ojs.aaai.org/index.php/AAAI/article/download/4946/4819">[Paper]</a>,
            <a href="https://github.com/MILVLG/activitynet-qa">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Web Videos</td>
		<td> 5.8K/58K/180</td>
		<td> Man</td>
	</tr>	
	<td><code></code></td>
		<td><a href="">[Paper]</a>,
            <a href="">[Dataset]</a></td>
		<td></td>
		<td> </td>
		<td> </td>
		<td> </td>
	</tr>	
</tbody >
</table>
</div>

### Leaderboards
### Paper Lists 

#### Survey

1. **Video Question Answering: Datasets, Algorithms and Challenges** `arxiv 2022` [[paper]]()
2. **Video question answering: a survey of models and datasets** `Mobile Networks and Applications 2021` [[paper]](https://link.springer.com/article/10.1007/s11036-020-01730-0)
3. **Video Question-Answering Techniques, Benchmark Datasets and Evaluation Metrics Leveraging Video Captioning: A Comprehensive Survey**  `IEEE Acess 2021` [[pdf]](https://ieeexplore.ieee.org/abstract/document/9350580) 
4. **Recent Advances in Video Question Answering: A Review of Datasets and Methods**  `ICPR Workshops 2021` [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-68790-8_27) 

