# sst_audio_record_upload_colab_utils
Library to download and import to add upload and record voices through notebook
# Manual utilization:
## First, clone zip file:
!git clone -q https://github.com/OussemaFr/sst_audio_record_upload_colab_utils
## Secondly, install library:
!pip install -q sst_audio_record_upload_colab_utils/sst_audio_record_upload_colab_utils.zip
## Finally, Import it:
from audio_record_upload.audio import record_audio, upload_audio
# Example:

def _record_audio(b):

    audio = record_audio(record_seconds, sample_rate=SAMPLE_RATE)

    _recognize(audio)
  
def _upload_audio(b):

    audio = upload_audio(sample_rate=SAMPLE_RATE)

    _recognize(audio)
