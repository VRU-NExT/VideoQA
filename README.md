# Video Question Answering: Datasets, Algorithms and Challenges

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

This repository contains a list of papers, codes, datasets, leaderboards of Video Question Answering (VideoQA). If you found any error, please don't hesitate to open an issue or pull request.

If you find this repository helpful for your work,  please kindly cite the following paper. The Bibtex are listed below:
<pre>
@article{zhong2022Video,
      title={Video Question Answering: Datasets, Algorithms and Challenges}, 
      author={Yaoyao Zhong and Wei Ji and Junbin Xiao and Yicong Li and Weihong Deng and Tat-Seng Chua},
      year={2022},
      article={arXiv preprint arXiv:2203.01225},
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
		<td> Multiple Source </td>
		<td> 109K/390K/-  </td>
		<td> Auto</td>
	</tr>
	<tr>
	<td><code>VideoQA</code></td>
		<td><a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14906/14319">[Paper]</a>,
            <a href="http://aliensunmin.github.io/project/video-language/">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Web Videos</td>
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
		<td> Web Videos </td>
		<td> 1.9K/50K/10</td>
		<td> Auto</td>
	</tr>	
	<tr>
	<td><code>MSRVTT-QA</code></td>
		<td><a href="http://staff.ustc.edu.cn/~hexn/papers/mm17-videoQA.pdf">[Paper]</a>,
            <a href="https://github.com/xudejing/video-question-answering">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Web Videos</td>
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
		<td> Synthetic Videos </td>
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
	<td><code>EgoVQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content_ICCVW_2019/papers/EPIC/Fan_EgoVQA_-_An_Egocentric_Video_Question_Answering_Benchmark_Dataset_ICCVW_2019_paper.pdf">[Paper]</a>,
            <a href="https://github.com/fanchenyou/EgoVQA/">[Dataset]</a></td>
		<td>VideoQA, Factoid</td>
		<td> Egocentric Videos</td>
		<td> 520/580/20-100 </td>
		<td> Man</td>
	</tr>	
	<td><code>CLERVER</code></td>
		<td><a href="https://arxiv.org/abs/1910.01442">[Paper]</a>,
            <a href="http://clevrer.csail.mit.edu/">[Dataset]</a>,
            <a href="https://github.com/chuangg/CLEVRER">[Code]</a></td>
		<td> VideoQA, Inference </td>
		<td> Synthetic Videos </td>
		<td> 10K/305K/5 </td>
		<td> Auto </td>
	</tr>	
	<td><code>TVQA+</code></td>
		<td><a href="https://arxiv.org/abs/1904.11574">[Paper]</a>,
            <a href="http://tvqa.cs.unc.edu/download_tvqa_plus.html">[Dataset]</a>,
            <a href="https://github.com/jayleicn/TVQAplus">[Code]</a></td>
		<td>MM VideoQA, Factoid</td>
		<td>TV</td>
		<td> 4.1K/29K/61</td>
		<td> Man</td>
	</tr>	
	<td><code>KnowIT VQA</code></td>
		<td><a href="https://arxiv.org/abs/1910.10706">[Paper]</a>,
            <a href="https://knowit-vqa.github.io/">[Dataset]</a>,
            <a href="https://github.com/noagarcia/knowit-rock">[Code]</a></td>
		<td>KB VideoQA, Factoid</td>
		<td> TV </td>
		<td> 12K/24K/20</td>
		<td> Man</td>
	</tr>	
	<td><code>TutorialVQA</code></td>
		<td><a href="https://arxiv.org/abs/1912.01046">[Paper]</a>,
            <a href="https://github.com/acolas1/TutorialVQAData">[Dataset]</a></td>
		<td> VideoQA, Inference</td>
		<td> Tutorial videos</td>
		<td> 408/6.1K/-</td>
		<td> Man</td>
	</tr>	
	<td><code>LifeQA</code></td>
		<td><a href="https://aclanthology.org/2020.lrec-1.536.pdf">[Paper]</a>,
            <a href="https://lit.eecs.umich.edu/lifeqa/">[Dataset]</a>,
            <a href="https://github.com/mmazab/LifeQA">[Code]</a></td>
		<td>MM VideoQA, Factoid</td>
		<td>Web Videos </td>
		<td> 275/2.3K/74 </td>
		<td> Man</td>
	</tr>	
	<td><code>PsTuts-VQA</code></td>
		<td><a href="https://arxiv.org/abs/2008.00544">[Paper]</a>,
            <a href="https://sites.google.com/view/pstuts-vqa/home">[Dataset]</a></td>
		<td> KB VideoQA, Factoid</td>
		<td> Tutorial Videos</td>
		<td> 76/17K/262</td>
		<td> Man </td>
	</tr>	
	<td><code>How2QA</code></td>
		<td><a href="https://arxiv.org/abs/2005.00200">[Paper]</a>,
            <a href="https://github.com/ych133/How2R-and-How2QA">[Dataset]</a>,
            <a href="https://github.com/linjieli222/HERO">[Code]</a></td>
		<td> MM VideoQA, Factoid</td>
		<td> Web Videos</td>
		<td> 22K/44K/60</td>
		<td> Man</td>
	</tr>	
	<td><code>V2C-QA</code></td>
		<td><a href="https://arxiv.org/abs/2003.05162">[Paper]</a>,
            <a href="https://github.com/jacobswan1/Video2Commonsense">[Dataset]</a>,
            <a href="https://github.com/jacobswan1/Video2Commonsense">[Code]</a></td>
		<td> CS VideoQA, Inference</td>
		<td> Web Videos</td>
		<td> 1.5K/37K/-</td>
		<td> Auto</td>
	</tr>	
	<td><code>NExT-QA</code></td>
		<td><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_NExT-QA_Next_Phase_of_Question-Answering_to_Explaining_Temporal_Actions_CVPR_2021_paper.pdf">[Paper]</a>,
            <a href="https://doc-doc.github.io/docs/nextqa.html">[Dataset]</a>,
            <a href="https://github.com/doc-doc/NExT-QA">[Code]</a></td>
		<td> VideoQA, Inference</td>
		<td> Web Videos</td>
		<td> 5.4K/52K/44</td>
		<td> Man</td>
	</tr>
	<td><code>AGQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Grunde-McLaughlin_AGQA_A_Benchmark_for_Compositional_Spatio-Temporal_Reasoning_CVPR_2021_paper.pdf">[Paper]</a>,
            <a href="https://cs.stanford.edu/people/ranjaykrishna/agqa/">[Dataset]</a>,
            <a href="https://github.com/madeleinegrunde/AGQA_baselines_code">[Code]</a></td>
		<td> VideoQA, Inference</td>
		<td> Homemade videos</td>
		<td> 9.6K/192M/30</td>
		<td> Auto</td>
	</tr>	
	<td><code>HowToVQA69M</code></td>
		<td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Just_Ask_Learning_To_Answer_Questions_From_Millions_of_Narrated_ICCV_2021_paper.pdf">[Paper]</a>,
            <a href="https://antoyang.github.io/just-ask.html">[Dataset]</a>,
            <a href="https://github.com/antoyang/just-ask">[Code]</a></td>
		<td> MM VideoQA, Factoid</td>
		<td> Web Videos</td>
		<td> 69M/69M/12</td>
		<td> Auto</td>
	</tr>	
	<td><code>iVQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Just_Ask_Learning_To_Answer_Questions_From_Millions_of_Narrated_ICCV_2021_paper.pdf">[Paper]</a>,
            <a href="https://antoyang.github.io/just-ask.html">[Dataset]</a>,
            <a href="https://github.com/antoyang/just-ask">[Code]</a></td>
		<td> MM VideoQA, Factoid</td>
		<td> Web Videos</td>
		<td> 10K/10K/18</td>
		<td> Man</td>
	</tr>	
	<td><code>SUTD-TrafficQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_SUTD-TrafficQA_A_Question_Answering_Benchmark_and_an_Efficient_Network_for_CVPR_2021_paper.pdf">[Paper]</a>,
            <a href="https://github.com/SUTDCV/SUTD-TrafficQA">[Dataset]</a>,
            <a href="https://github.com/SUTDCV/SUTD-TrafficQA">[Code]</a></td>
		<td> VideoQA, Inference </td>
		<td> Traffic scenes </td>
		<td> 10K/62K/- </td>
		<td> Man </td>
	</tr>	
	<td><code>Env-QA</code></td>
		<td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Env-QA_A_Video_Question_Answering_Benchmark_for_Comprehensive_Understanding_of_ICCV_2021_paper.pdf">[Paper]</a>,
            <a href="https://envqa.github.io/">[Dataset]</a></td>
		<td> MM VideoQA, Factoid </td>
		<td> Egocentric Videos </td>
		<td> 23K/85K/20</td>
		<td> Auto, Man</td>
	</tr>	
	<td><code>Pano-AVQA</code></td>
		<td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.pdf">[Paper]</a>,
            <a href="https://github.com/hs-yn/PanoAVQA">[Dataset]</a></td>
		<td> MM VideoQA, Factoid</td>
		<td> 360° Videos </td>
		<td> 5.4K/51.7K/-</td>
		<td> Man</td>
	</tr>	
	<td><code>DramaQA</code></td>
		<td><a href="https://arxiv.org/abs/2005.03356">[Paper]</a>,
            <a href="https://dramaqa.snu.ac.kr/">[Dataset]</a>,
            <a href="https://github.com/liveseongho/DramaQAChallenge2020">[Dataset]</a></td>
		<td> MM VideoQA, Inference </td>
		<td> TV</td>
		<td> 23K/17K/- </td>
		<td> Man </td>
	</tr>	
	<td><code>TGIF-QA-R</code></td>
		<td><a href="https://dl.acm.org/doi/abs/10.1145/3474085.3475193">[Paper]</a>,
            <a href="https://github.com/PengLiang-cn/PGAT">[Dataset]</a></td>
		<td> VideoQA, Factoid </td>
		<td> GIF </td>
		<td> 71K/165K/3  </td>
		<td> Auto </td>
	</tr>	
	<td><code>KnowIT-X VQA</code></td>
		<td><a href="https://arxiv.org/abs/2110.13395">[Paper]</a>,
            <a href="https://knowit-vqa.github.io/">[Dataset]</a></td>
		<td>KB VideoQA, Factoid</td>
		<td> TV </td>
		<td> 12.1K/21.4K/20</td>
		<td> Man </td>
	</tr>	
	<td><code>ASRL-QA</code></td>
		<td><a href="https://arxiv.org/abs/2104.03762">[Paper]</a>,
            <a href="https://github.com/TheShadow29/Video-QAP">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Web Videos </td>
		<td> 35K/162K/36.2</td>
		<td> Auto </td>
	</tr>	
	<td><code>Charades-SRL-QA</code></td>
		<td><a href="https://arxiv.org/abs/2104.03762">[Paper]</a>,
            <a href="https://github.com/TheShadow29/Video-QAP">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Homemade videos </td>
		<td> 9.5K/71K/29</td>
		<td> Auto </td>
	</tr>	
	<td><code>MedVidQA</code></td>
		<td><a href="https://arxiv.org/pdf/2201.12888.pdf">[Paper]</a>,
            <a href="https://github.com/deepaknlp/MedVidQACL">[Dataset]</a></td>
		<td> VideoQA, Factoid</td>
		<td> Medical Instructional Videos</td>
		<td> 899/3K/-</td>
		<td> Man</td>
	</tr>	
	<td><code>NEWSKVQA</code></td>
		<td><a href="https://arxiv.org/abs/2202.04015">[Paper]</a>,
            <a href="https://drive.google.com/file/d/1kK7fjwCZi0SLGGMHAENE8_Eofk_mVC15/view">[Dataset]</a></td>
		<td> KB VideoQA, </td>
		<td> News Videos</td>
		<td> 12K/1M/30</td>
		<td> Auto</td>
	</tr>	
</tbody >
</table>
</div>

### Paper Lists 

#### Survey

1. **Video Question Answering: Datasets, Algorithms and Challenges** `arXiv 2022` [[Paper]](https://arxiv.org/abs/2203.01225).
2. **Video question answering: a survey of models and datasets** `Mobile Networks and Applications 2021` [[Paper]](https://link.springer.com/article/10.1007/s11036-020-01730-0).
3. **Video Question-Answering Techniques, Benchmark Datasets and Evaluation Metrics Leveraging Video Captioning: A Comprehensive Survey**  `IEEE Acess 2021` [[Paper]](https://ieeexplore.ieee.org/abstract/document/9350580). 
4. **Recent Advances in Video Question Answering: A Review of Datasets and Methods**  `ICPR Workshops 2021` [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-68790-8_27). 

#### Early Works (Varients of RNNs)
1. **Uncovering the temporal context for video question answering** `arXiv 2015, IJCV 2017` [[paper]](https://arxiv.org/pdf/1511.04670.pdf)[[Code]](https://github.com/ffmpbgrnn/VideoQA).
2. **Tgif-qa: Toward spatio-temporal reasoning in visual question answering** `CVPR 2017` [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jang_TGIF-QA_Toward_Spatio-Temporal_CVPR_2017_paper.pdf)[[Code]](https://github.com/YunseokJANG/tgif-qa).
3. **End-to-end concept word detection for video captioning, retrieval, and question answering** `CVPR 2017` [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yu_End-To-End_Concept_Word_CVPR_2017_paper.pdf)[[3rd Party Code]](https://github.com/YuliaNovskaya/cv31).
4. **Video question answering via gradually refined attention over appearance and motion** `ACMMM 2017` [[paper]](http://staff.ustc.edu.cn/~hexn/papers/mm17-videoQA.pdf)[[Code]](https://github.com/xudejing/video-question-answering).
5. **Video question answering via hierarchical dual-level attention network learning** `ACMMM 2017` [[paper]](https://dl.acm.org/doi/abs/10.1145/3123266.3123364).
6. **Video question answering via attribute-augmented attention network learning** `SIGIR 2017` [[paper]](https://arxiv.org/pdf/1707.06355.pdf).
7. **MarioQA: Answering Questions by Watching Gameplay Videos** `ICCV 2017` [[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Mun_MarioQA_Answering_Questions_ICCV_2017_paper.pdf)[[Code]](https://github.com/JonghwanMun/MarioQA).
8. **Video Question Answering via Hierarchical Spatio-Temporal Attention Networks** `IJCAI 2017` [[paper]](https://www.ijcai.org/proceedings/2017/0492.pdf)[[Code]](https://github.com/s0sbazinga/videoqa-stan).
9. **Unifying the video and question attentions for open-ended video question answering** `TIP 2017` [[paper]](https://ieeexplore.ieee.org/abstract/document/8017608)[[Code]](https://github.com/ZJULearning/videoqa).
10. **Tvqa: Localized, compositional video question answering** `EMNLP 2018` [[paper]](https://arxiv.org/abs/1809.01696)[[Code]](https://github.com/jayleicn/TVQA).
11. **Explore multi-step reasoning in video question answering** `ACMMM 2018` [[paper]](https://dl.acm.org/doi/abs/10.1145/3240508.3240563)[[Code]](https://github.com/SVQA-founder/SVQA/tree/master/code).
12. **Hierarchical relational attention for video question answering** `ICIP 2018` [[paper]](https://eprints.qut.edu.au/122718/1/icip_2018_eprint.pdf).
13. **** `` [[paper]]()[[Code]]().
14. 


#### Memory Networks
1. **DeepStory: Video Story QA by Deep Embedded Memory Networks** `IJCAI 2017` [[paper]](https://arxiv.org/ftp/arxiv/papers/1707/1707.00836.pdf)[[Code]](https://github.com/Kyung-Min/Deep-Embedded-Memory-Networks).
2. **Motion-appearance co-memory networks for video question answering** `CVPR 2018` [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gao_Motion-Appearance_Co-Memory_Networks_CVPR_2018_paper.pdf).
3. **Multimodal dual attention memory for video story question answering** `ECCV 2018` [[paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Kyungmin_Kim_Multimodal_Dual_Attention_ECCV_2018_paper.pdf).
4. **Movie Question Answering: Remembering the Textual Cues for Layered Visual Contents** `AAAI 2018` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/12253).
5. **A better way to attend: Attention with trees for video question answering** `TIP 2018` [[paper]](https://arxiv.org/pdf/1909.02218.pdf).
6. **The forgettable-watcher model for video question answering** `Neurocomputing 2018` [[paper]](https://www.sciencedirect.com/science/article/pii/S0925231218308075).
7. **Heterogeneous memory enhanced multimodal attention model for video question answering** `CVPR 2019` [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Fan_Heterogeneous_Memory_Enhanced_Multimodal_Attention_Model_for_Video_Question_Answering_CVPR_2019_paper.pdf)[[Code]](https://github.com/fanchenyou/HME-VideoQA).
8. **Progressive attention memory network for movie story question answering** `CVPR 2019` [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Progressive_Attention_Memory_Network_for_Movie_Story_Question_Answering_CVPR_2019_paper.pdf).
9. **Memory augmented deep recurrent neural network for video question answering** `TCSVT 2019` [[paper]](https://ieeexplore.ieee.org/abstract/document/8845771).
10. **** `` [[paper]]()[[Code]]().
11. 

#### Transformer
1. **Beyond rnns: Positional self-attention with co-attention for video question answering** `AAAI 2019` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4887)[[Code]](https://github.com/lixiangpengcs/PSAC).
2. **Multi-Question Learning for Visual Question Answering** `AAAI 2020` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6794).
3. **BERT Representations for Video Question Answering** `WACV 2020` [[paper]](https://openaccess.thecvf.com/content_WACV_2020/papers/Yang_BERT_representations_for_Video_Question_Answering_WACV_2020_paper.pdf)[[Code]]().
4. **HERO: Hierarchical Encoder for Video+Language Omni-representation Pre-training** `` [[paper]](https://arxiv.org/abs/2005.00200)[[Code]](https://github.com/linjieli222/HERO).
5. **MMFT-BERT: Multimodal Fusion Transformer with BERT Encodings for Visual Question Answering** `EMNLP 2020` [[paper]](https://arxiv.org/abs/2010.14095)[[Code]](https://github.com/aurooj/MMFT-BERT).
6. **** `` [[paper]]()[[Code]](). 
7. **** `` [[paper]]()[[Code]](). 

#### Graph Neural Networks
1. **Location-Aware Graph Convolutional Networks for Video Question Answering** `AAAI 2020` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6737).
2. **Reasoning with heterogeneous graph alignment for video question answering** `AAAI 2020` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6767)[[Code]](https://github.com/Jumpin2/HGA).
3. **Knowledge-based video question answering with unsupervised scene descriptions** `ECCV 2020` [[paper]](https://arxiv.org/pdf/2007.08751.pdf?ref=https://githubhelp.com)[[Code]]().
4. 

#### Modular Networks
1. **Question-aware tube-switch network for video question answering** `ACMMM 2019` [[paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3350969).
2. **Open-Ended Long-Form Video Question Answering via Hierarchical Convolutional Self-Attention Networks** `IJCAI 2019` [[paper]](https://arxiv.org/abs/1906.12158).
3. **Hierarchical conditional relation networks for video question answering** `CVPR 2020` [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Hierarchical_Conditional_Relation_Networks_for_Video_Question_Answering_CVPR_2020_paper.pdf)[[Code]](https://github.com/thaolmk54/hcrn-videoqa).
4. **** `` [[paper]]()[[Code]]().
5. 

#### Neural-Symbolic
1. **Clevrer: Collision events for video representation and reasoning** `ICLR 2020` [[paper]](https://arxiv.org/abs/1910.01442)[[Code]](https://github.com/chuangg/CLEVRER).
2. **** `` [[paper]]()[[Code]]().
3. 

#### Flexibly Designed Networks
1. **A joint sequence fusion model for video question answering and retrieval** `ECCV 2018` [[paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Youngjae_Yu_A_Joint_Sequence_ECCV_2018_paper.pdf)[[Code]](https://github.com/yj-yu/lsmdc).
2. **Structured Two-Stream Attention Network for Video Question Answering** `AAAI 2019` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4602).
3. **Multi-interaction Network with Object Relation for Video Question Answering** `ACMMM 2019` [[paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3351065).
4. **Learnable aggregating net with diversity learning for video question answering** `ACMMM 2019` [[paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3350971).
5. **Compositional attention networks with two-stream fusion for video question answering** `TIP 2019` [[paper]](https://ieeexplore.ieee.org/abstract/document/8839734).
6. **Frame augmented alternating attention network for video question answering** `TMM 2019` [[paper]](https://ieeexplore.ieee.org/abstract/document/8811730)[[Code]](https://github.com/wannature/video-qa-FAAAN).
7. **Spatiotemporal-Textual Co-Attention Network for Video Question Answering** `TOMM 2019` [[paper]](https://dl.acm.org/doi/abs/10.1145/3320061).
8. **Modality shifting attention network for multi-modal video question answering** `CVPR 2020` [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kim_Modality_Shifting_Attention_Network_for_Multi-Modal_Video_Question_Answering_CVPR_2020_paper.pdf).
9. **Divide and conquer: Question-guided spatio-temporal contextual attention for video question answering** `AAAI 2020` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6766).
10. **Dual Hierarchical Temporal Convolutional Network with QA-Aware Dynamic Normalization for Video Story Question Answering** `ACMMM 2020` [[paper]](https://dl.acm.org/doi/abs/10.1145/3394171.3413649). 

#### Others

##### Reforced Decoder
1. **Open-Ended Long-form Video Question Answering via Adaptive Hierarchical Reinforced Networks** `IJCAI 2018` [[paper]](https://www.ijcai.org/Proceedings/2018/0512.pdf).
2. **Long-form video question answering via dynamic hierarchical reinforced networks** `TIP 2019` [[paper]](https://ieeexplore.ieee.org/abstract/document/8737880).

##### Knowledge Incorporation 
1. **Video question answering via knowledge-based progressive spatial-temporal attention network** `TOMM 2019` [[paper]](https://dl.acm.org/doi/abs/10.1145/3321505).
2. **KnowIT VQA: Answering Knowledge-Based Questions about Videos** `AAAI 2020` [[paper]](https://github.com/noagarcia/knowit-rock)[[Code]](https://github.com/noagarcia/knowit-rock).

##### Commonsense Incorporation 
1. **Video2Commonsense: Generating Commonsense Descriptions to Enrich Video Captioning** `EMNLP 2020` [[paper]](https://arxiv.org/abs/2003.05162)[[Code]]().

##### Multi-task Learning
1. **Gaining extra supervision via multi-task learning for multi-modal video question answering** `IJCNN 2019` [[paper]](https://ieeexplore.ieee.org/abstract/document/8852087).
2. **TVQA+: Spatio-Temporal Grounding for Video Question Answering** `ACL 2020` [[paper]](https://arxiv.org/abs/1904.11574)[[Code]](https://github.com/jayleicn/TVQAplus).

##### Input Data
1. **Data augmentation techniques for the Video Question Answering task** `ECCV 2020` [[paper]](https://arxiv.org/pdf/2008.09849.pdf).
2. 



### Leaderboards
