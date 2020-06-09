
## Summary of included files

- The project proposal.
- The notebooks with the machine learning process and named after the models resnet50 and resnet34.
- The python web application.
- The project report.



## To deploy the web app on [Render](https://render.com)

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The web app described here is up at https://plantdiseaseml.onrender.com, Test it out with images of plant leaves! 

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.

### Screenshots of the app:
- i
[![Screenshot-2020-06-09-at-13-53-37.png](https://i.postimg.cc/3xmfPL3s/Screenshot-2020-06-09-at-13-53-37.png)](https://postimg.cc/BjZCFBLp)
- ii
[![Screenshot-2020-06-09-at-13-52-58.png](https://i.postimg.cc/rFdP9V3F/Screenshot-2020-06-09-at-13-52-58.png)](https://postimg.cc/mtsjLsT0)


References
- Original crowdai dataset https://github.com/MichaelGerhard/PlantDiseaseData
- Resnet, https://neurohive.io/en/popular-networks/resnet/
-  David Hughes paper, https://arxiv.org/ftp/arxiv/papers/1604/1604.03169.pdf
- Viridiana Romero Martinez's medium article https://medium.com/datadriveninvestor/creating-an-ai-app-that-detect-diseases-in-plants-using-facebooks-deep-learning-platform-pytorch-15faaeb6bec3
- https://towardsdatascience.com/create-and-deploy-an-image-classifier-using-fastai-and-render-in-15-mins-947f9de42d21