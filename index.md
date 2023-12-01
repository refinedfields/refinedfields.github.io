<p align="justify">Modeling large-scale scenes from unconstrained image collections in-the-wild has proven to be a major challenge in computer vision. Existing methods tackling in-the-wild neural rendering operate in a closed-world setting, where knowledge is limited to a scene's captured images within a training set. We propose EvE, which is, to the best of our knowledge, the first method leveraging generative priors to improve in-the-wild scene modeling. We employ pre-trained generative networks to enrich K-Planes representations with extrinsic knowledge. To this end, we define an alternating training procedure to conduct optimization guidance of K-Planes trained on the training set. We carry out extensive experiments and verify the merit of our method on synthetic data as well as real tourism photo collections. EvE enhances rendered scenes with richer details and outperforms the state of the art on the task of novel view synthesis in-the-wild.</p>

## Method
![Figure](assets/css/schema.svg)

We learn a scene through two alternating stages.
_Scene fitting_ optimizes our K-Planes representation to reproduce the images in the training set, as traditionally done in neural rendering techniques.
_Scene enriching_ finetunes a pre-trained generative prior to this K-Planes representation, and then infers a new one, which will subsequently be corrected by scene fitting.

## In-the-wild Renders
<center>
    <div>
<!--         <video width="30%" height="30%" autoplay muted loop playsinline>
            <source src="assets/css/brandenburg.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video> -->
        <video width="30%" height="30%" autoplay muted loop playsinline>
            <source src="assets/css/sacre.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="30%" height="30%" autoplay muted loop playsinline>
            <source src="assets/css/trevi.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
    </div>
</center>

## Synthetic Renders
<center>
    <div>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/chair.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/drums.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/ficus.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/hotdog.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
    </div>
    <div>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/lego.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/materials.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/mic.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
        <video width="23%" height="23%" autoplay muted loop playsinline>
            <source src="assets/css/ship.mp4" type="video/mp4" style="display: inline-block;">
            Your browser does not support the video tag.
        </video>
    </div>
</center>

## Citation
```
@inproceedings{EvE,
  title={},
  author={},
  booktitle={},
  pages={},
  year={2024}
}
```
