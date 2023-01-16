# Sign Language Video Anonymization
Publication:
Xia, Zhaoyang, Yuxiao Chen, Qilong Zhangli, Matt Huenerfauth, Carol Neidle, and Dimitri Metaxas. Sign language video anonymization. In Proceedings of the LREC2022 10th Workshop on the Representation and Processing of Sign Languages: Multilingual Sign Language Resources (LREC), pages 202–211, 2022 
Paper address: [PDF](https://www.sign-lang.uni-hamburg.de/lrec/pub/22038.pdf)

## This repository contains demos for Sign Language-Video Anonymization paper in LREC'22 sign-lang workshop.

## Example Anonymization results:
![Screenshot](demos/dsp_example.gif)
![Screenshot](demos/lrp_example.gif)



Citation: 
```
@inproceedings{xia-etal-2022-sign,
    title = "Sign Language Video Anonymization",
    author = "Xia, Zhaoyang  and
      Chen, Yuxiao  and
      Zhangli, Qilong  and
      Huenerfauth, Matt  and
      Neidle, Carol  and
      Metaxas, Dimitri",
    booktitle = "Proceedings of the LREC2022 10th Workshop on the Representation and Processing of Sign Languages: Multilingual Sign Language Resources",
    month = jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2022.signlang-1.32",
    pages = "202--211",
    abstract = "Deaf signers who wish to communicate in their native language frequently share videos on the Web. However, videos cannot preserve privacy{---}as is often desirable for discussion of sensitive topics{---}since both hands and face convey critical linguistic information and therefore cannot be obscured without degrading communication. Deaf signers have expressed interest in video anonymization that would preserve linguistic content. However, attempts to develop such technology have thus far shown limited success. We are developing a new method for such anonymization, with input from ASL signers. We modify a motion-based image animation model to generate high-resolution videos with the signer identity changed, but with the preservation of linguistically significant motions and facial expressions. An asymmetric encoder-decoder structured image generator is used to generate the high-resolution target frame from the low-resolution source frame based on the optical flow and confidence map. We explicitly guide the model to attain a clear generation of hands and faces by using bounding boxes to improve the loss computation. FID and KID scores are used for the evaluation of the realism of the generated frames. This technology shows great potential for practical applications to benefit deaf signers.",
}
```








