- š Hi, Iām @joy092417
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
joy092417/joy092417 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Copy the patch file to the root directory of Alexa AVS sample app. Please replace $ALEXA_AVS_SAMPLE_APP_PATH with the actual path where you
# cloned the Alexa AVS sample app repository, and replace $SNOWBOY_ROOT_PATH with the actual path where you clone the Snowboy repository
cd $ALEXA_AVS_SAMPLE_APP_PATH
cp $SNOWBOY_PATH/resource/alexa/alexa-avs-sample-app/avs-kittai.patch ./

# Apply the patch, this will modify the scripts setup.sh and pi.sh
patch < avs-kittai.patch
