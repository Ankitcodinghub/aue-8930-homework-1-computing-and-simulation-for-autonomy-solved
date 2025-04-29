# aue-8930-homework-1-computing-and-simulation-for-autonomy-solved
**TO GET THIS SOLUTION VISIT:** [AuE 8930 Homework 1-Computing and Simulation for Autonomy Solved](https://www.ankitcodinghub.com/product/homework-1-aue-8930-computing-and-simulation-for-autonomy-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113000&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AuE 8930 Homework 1-Computing and Simulation for Autonomy Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Question 1

Training a Pytorch deep learning model on Palmetto cluster (60 points)

(Recommended to use Jupyter Notebook in Palmetto OpenOnDemand for edit/debug/run)

Palmetto Cluster and Setup

• Login into your Palmetto account &amp; request a node with required specifications by specifying a hardware resource configuration, making sure to include GPU. (For below all questions, make sure to use same configuration).

• Transfer the sample code into your account using Globus (if using Terminal) or JupterHub.

A conda virtual environment allows you to run/install a version of Python and package as needed within it.

This environment, once created/modified is saved and can be accessed later through the code: conda create -n NAME_OF_ENV python=3.6 # (Create Environment) source activate NAME_OF_ENV # (Activate Environment) source deactivate NAME_OF_ENV # (Deactivate Environment)

Install necessary packages in the terminal

Add cuda and cudnn module:

module add cuda/11.1.1-gcc/9.5.0

module add cudnn/8.0.5.39-11.1-gcc/9.5.0-cu11_1

Install Pytorch and Torchvision libraries using conda (reference)

conda install pytorch torchvision torchaudio cudatoolkit=11.1 -c pytorch-lts -c nvidia

Generate Kernel for JupyterHub

It means your Jupyter notebook is running in the default python environment, but your torch module is installed in your Conda virtual environment. You will need to run Jupyter notebook in your virtual env.

Here is a tutorial: https://janakiev.com/blog/jupyter-virtual-envs/

Training deep learning model for Image Classification

Sample code is in Canvas/Files can be downloaded from: Homework_1_sample_code.zip

which includes: base.ipynb, common.py and models.py. The base.ipynb allows you to use your web browser as the GUI to run/edit/debug.

You also need to make ‘data’ and ‘models’ folder before running the ‘base.ipynb’. The directory structure should look like:

There are multiple steps in the sample code files:

• Load the training and test datasets from torchvision (reference) Training Data can be obtained from various online sources, self-procured or can even be imported from a library like Pytorch.

• Define a Convolutional Neural Network (reference)

• Define a loss function (reference)

• Train the network on the training data with different number of Epochs (reference).

(1) Show screenshots of successful installation and procedure of the setup. (15 points)

(2) Run the existing sample code “base.ipynb” (5 points)

During the training, what’s your GPU usage percentage? (You can open another terminal and use “nvidia-smi –l” to monitor the usage info of GPU and GPU memory.)

(3) Modify the code for better performance (change the batch size) (10 points) During the training, what’s your GPU usage percentage?

(4) Modify the code for better performance (use two GPUs) (10 points)

During the training, what’s your GPU info percentage? (TIPS: reference API)

(5) Plot the accuracy against the number of training Epochs on a Graph. (10 points) (TIPS: you need to import matplotlib, modify the code of “for epoch in range (EPOCHS):” by saving the “epoch” and “train_acc”, and plot its relationship in the end)

(6) Could you improve on the network model, train it for better accuracy? (optional, 5 points) (This question is optional. Extra 5 points until reach the cap of 100)

(7) Perform a model inference for a certain image, which you can choose from anywhere. The image shall include the object which belongs to the category of the training dataset. (10 points)

(TIPS: if you are using CIFAR10 datasets, its categories are shown in this reference)

Question 2

Write a 2~3 pages survey report on a particular High-Performance-Computing application related to engineering/vehicles (40 points). The grading of this question will be based on the contents which the survey covers:

– What is the problem to be solved (5 points);

– The importance of the problem to be solved (5 points);

– The challenges of solving this problem (10 points);

– Existing solutions of solving this problem (15 points);

– Other grading factors (such as novelty, organization, etc.) (5);

* You are encouraged to include any drawing/table in the report;

* Attention: use like [1] to cite a content you referred to, with reference list in the end. You should never literally copy contents from other places;

TIPS: you should survey and read multiple academic papers, academic papers. Then, summarize for the above.
