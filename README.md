# steam-pubg-config
efekleri en aza çekerek, grafikten belli miktar ödün vererek oluşturduğum config ayarı

C:\Users\KULLANICI\AppData\Local\TslGame\Saved\Config\WindowsNoEditor\Engine.ini
* Yoluna bu kodları ekleyin.
* Ekledikten sonra Engine.ini dosyasına > sağ tık > özellikler > salt okunur yap.
* Sonra oyuna girebilirsin.
Not: Oyundan ayar değiştirirsen dosyalar çakışır. Değiştirden sonra oyunu kapat, Engine.ini dosyasını ilk haline çevirip ayarları tekrarla.
Not2: Sistemim RTX2060 Evo Super 6b, AMD Ryzen 5 3600. Bende işe yaradı sende yaramayabilir. 
Not3: Eğer işe yaramazsa kodları kendi sistemine göre düzenleyebilirsin.

[SystemSettings]
r.setres=1680x1050f ; oyundaki kendi çözünürlüğün
r.ScreenPercentage=85
r.VSync=0
r.ShadowQuality=1
r.Shadow.CSM.MaxCascades=0
r.Shadow.MaxResolution=16
r.Shadow.DistanceScale=0
r.Shadow.RadiusThreshold=1.0
r.Shadow.FadeResolution=8
r.Shadow.PerObject=0
r.DistanceFieldShadowing=0
r.Shadow.PreShadowResolutionFactor=0.1
r.Shadow.CSM.TransitionScale=0
r.Shadow.FadeExponent=0.1
r.AllowLandscapeShadows=0
r.Shadow.MaxCSMResolution=8
r.EffectsQuality=1
r.PostProcessAAQuality=4
r.PostProcessQuality=1
r.LightShafts=0
r.BloomQuality=0
r.LensFlareQuality=0
r.DepthOfFieldQuality=0
r.RefractionQuality=0
r.Fog=0
r.VolumetricFog=0
r.MotionBlurQuality=0
r.SSR.Quality=0
r.SceneColorFringeQuality=0
r.AmbientOcclusionLevels=0
r.AOQuality=0
r.AOMaxQuality=0
r.EyeAdaptationQuality=0
r.TranslucencyLightingVolumeDim=1
r.TextureStreaming=1
r.MaxAnisotropy=4
r.MipMapLODBias=-1.0
foliage.DensityScale=0
grass.DensityScale=0
r.ViewDistanceScale=0.9
r.LandscapeLODDistributionScale=2.0
r.DetailMode=0
r.SeparateTranslucency=0
r.TranslucencyVolumeBlur=0
r.VolumetricRenderTarget=0
r.DBuffer=0
r.MinScreenRadiusForDepthPrepass=0.1
r.ParticleLODBias=8
r.ForceLOD=1
r.EmitterSpawnRateScale=0.1
r.LightFunctionQuality=0
r.LightShaftQuality=0
r.ParallelShadows=1
r.MinScreenRadiusForLights=1.0
r.RenderTargetPoolMin=300
r.AllowPrecomputedVisibility=1
r.OnlyStreamInTextures=1
r.DisableLODFade=1
r.Refraction=0
r.OptimizeMRT=1
r.SceneRenderTargetResizeMethod=2
r.MinScreenRadiusForCSMDepth=100
r.StationaryLightOverlap=0
r.LODDistanceFactor=0.9
r.AllowOcclusionQueries=1
r.MaterialQualityLevel=0
r.Streaming.HLODStrategy=2
r.LightMaxDrawDistanceScale=0.1
r.SkeletalMeshLODBias=2
r.ParticleLightQuality=0
r.ReflectionEnvironment=0
r.TranslucencyLightingVolume=0
r.MaxQualityMode=1
r.DefaultFeature.MotionBlur=0
r.DefaultFeature.AntiAliasing=0
r.DefaultFeature.Bloom=0
r.DefaultFeature.AutoExposure=0
r.DefaultFeature.LensFlare=0
r.Tonemapper.Quality=0
r.Tonemapper.Sharpen=0.5
r.SimpleDynamicLighting=1
r.Upscale.Quality=0
r.FastBlurThreshold=0
r.GTSyncType=0
r.OneFrameThreadLag=1
r.FinishCurrentFrame=1
r.GPUBufferSyncMode=0
r.ForceAllCores=1
r.OptimizeForUAVPerformance=1
r.Streaming.PoolSize=4096 ; Ekran Kartına göre ayarla (4GB için 3072, 6GB için 4096)
r.Streaming.LimitPoolSizeToVRAM=1
r.Texture.MaxAnisotropy=8
r.Streaming.FullyLoadUsedTextures=0
p.Cloth.MaxIterations=1
physics.AllowAsync=1
r.DynamicResolution=0
r.HZB=1
r.TemporalAASamples=32
r.TemporalAACurrentFrameWeight=0.2
