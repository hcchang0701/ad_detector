You are welcome to use any language you feel familiar for this project.

About the RefrenceCode folder:
	This reference code only provides you some reference about how to play audio file. You need to program your own part to make the audio part and video part synchronized. As long as you can find ways to read *.rgb format and *.wav format, and then synchronize the video and audio parts, it will be okay. You can use libraries to read them, especially for the *.wav file. 
	
	Actually the purpose of audio data is making index for the comparison. Therefore, as long as you can make a index from audio data & do the comparison. You don't need to worry about data type you are using.

About the dataset folder: (you can download from Google Driver as shown in dataset.txt)
	For Video Part:
	  Video Frame Size: 480*270
	  Video Data format: RGB format similar with assignments
	  Video FPS: 30 frames/second

	For Audio Part:
	  Auido Sampling Rate: 48000 HZ
	  Audio Channels : 1 mono
	  Bits per sample: 16
	  
  "Videos" folder: 
    include the video files you need to process. There are two ads originally inserted here. Logs are also included in the video file.
	data_test1: a 5 minutes video you need to process your tasks
	   5 minutes video part: data_test1.rgb
	   5 minutes Audio part: data_test1.wav
	   5 minutes Audio/Video AVI: data_test1_cmp.avi (this is the compressed video only for your reference to review the video. You should use .rgb and .wav for your processing)
	   
  "Ads" folder: 
    include ads you need to insert into the processing videos.
	Subway_Ad_15s: a 15 seconds subway ad
	   15 seconds video part: Subway_Ad_15s.rgb
	   15 seconds Audio part: Subway_Ad_15s.wav
	   15 seconds Audio/Video AVI: Subway_Ad_15s_cmp.avi (this is the compressed video only for your reference to review the video. You should use .rgb and .wav for your processing)

	Starbucks_Ad_15s:  a 15 seconds starbucks ad
	   15 seconds video part: Starbucks_Ad_15s.rgb
	   15 seconds Audio part: Starbucks_Ad_15s.wav
	   15 seconds Audio/Video AVI: Starbucks_Ad_15s_cmp.avi (this is the compressed video only for your reference to review the video. You should use .rgb and .wav for your processing)
	   
  "Brand Images" folder: 
    Include brand/logo images in rgb format with 480*270 as resolution. 
	The BMP files are only for your reference to review the images and you should use the .rgb files.