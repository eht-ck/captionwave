# CaptionWave

CaptionWave is a Next.js application that allows users to add captions/subtitles to videos, customize the appearance of captions, and download the generated subtitles file (SRT) along with the video embedded with captions.

## Features

- Upload a video and receive automated captions using AWS Transcriber.
- Customize the appearance of captions with an in-screen editor.
- Download the generated subtitles file (SRT) and video with embedded captions.
- Integration with AWS S3 bucket for video storage.

## Architecture
![image](https://github.com/eht-ck/captionwave/assets/95522110/91e7bfd8-98f7-4ac2-acef-3cd87b5704df)

## Video Demonstartion


Uploading Project ReadME - Made with Clipchamp.mp4…



## Getting Started

1. **Clone the Repository:**

    ```bash
      https://github.com/eht-ck/captionwave.git
    ```

2. **Install Dependencies:**

    ```bash
    cd CaptionWave
    yarn install
    ```

3. **Set Up AWS Credentials:**

    Create an AWS account, set up an S3 bucket, and obtain AWS Access Key ID and Secret Access Key. Set these credentials in your environment variables.

    ```bash
    export AWS_ACCESS_KEY=your-access-key
    export AWS_SECRET_ACCESS_KEY=your-secret-access-key
    export BUCKET_NAME=your-bucker-name
    ```

4. **Run the Application:**

    ```bash
    yarn dev
    ```

    Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. **Upload a Video:**

    - Navigate to the application and upload a video.
    - AWS Transcriber will automatically generate captions for the video.

2. **Customize Captions:**

    - Use the in-screen editor to customize the appearance of captions.
    - Adjust font size, color, background, etc.

3. **Download Subtitles:**

    - Click on the "Download SRT" button to download the subtitles file.

4. **Download Video with Captions:**

    - Click on the "Apply Captions" button to embed captions on the video.
    - Download the video with embedded captions.

## Contributing

Feel free to contribute to the development of CaptionWave. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [AWS S3](https://aws.amazon.com/s3/)
- [AWS Transcribe](https://aws.amazon.com/transcribe/)
- [Tailwind CSS](https://tailwindcss.com/)

Happy captioning!
