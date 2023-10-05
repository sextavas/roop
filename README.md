Removed the NSFW blocker that is included in the main repo.....
Take a video and replace the face in it with a face of your choice. You only need one image of the desired face. No dataset, no training.

https://colab.research.google.com/github/devIndustrial/roop/blob/main/based_roop.ipynb

![demo-gif](demo.gif)

options:
  -h, --help            show this help message and exit
  -f SOURCE_IMG, --face SOURCE_IMG
                        use this face
  -t TARGET_PATH, --target TARGET_PATH
                        replace this face
  -o OUTPUT_FILE, --output OUTPUT_FILE
                        save output to this file
  --keep-fps            maintain original fps
  --keep-frames         keep frames directory
  --all-faces           swap all faces in frame
  --max-memory MAX_MEMORY
                        maximum amount of RAM in GB to be used
  --cpu-cores CPU_CORES
                        number of CPU cores to use
  --gpu-threads GPU_THREADS
                        number of threads to be use for the GPU
  --gpu-vendor {apple,amd,intel,nvidia}
                        choice your GPU vendor

## Credits
- [henryruhs](https://github.com/henryruhs): for being an irreplacable contributor to the project
- [ffmpeg](https://ffmpeg.org/): for making video related operations easy
- [deepinsight](https://github.com/deepinsight): for their [insightface](https://github.com/deepinsight/insightface) project which provided a well-made library and models.
- and all developers behind libraries used in this project.
