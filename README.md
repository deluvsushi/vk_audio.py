# vk_audio.py
Mobile-API for interacting with audios in [vkontakte](https://vk.com) social network

## Examples
```python3
import vk_audio
VkAudioClient = vk_audio.VkAudioClient(access_token="")
popular_audios = VkAudioClient.get_popular_audios(count=100)
print(popular_audios)
```
