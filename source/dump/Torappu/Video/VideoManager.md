# VideoManager

**Namespace:** `Torappu.Video`


## Fields

- `AbstractMediaPlayerHolder _mediaPlayer`

- `CriWareInitializer m_criWareInitializer`

- `CriWareErrorHandler m_errorHandler`


## Methods

- `AbstractMediaPlayerHolder InstaniateMediaPlayer(Transform)`

- `Boolean CheckVideoExist(String)`

- `String GetVideoFullPath(String)`

- `String TreatVideoPath(String)`

- `Boolean IsMp4VideoPath(String)`

- `Void OnInitSDK(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Video
public class VideoManager : PersistentSingleton`1, IHotfixable, ISingletonNotAutoCreate
{
	private AbstractMediaPlayerHolder _mediaPlayer; // 0x18
	private CriWareInitializer m_criWareInitializer; // 0x20
	private CriWareErrorHandler m_errorHandler; // 0x28
	private static DelegateBridge __Hotfix0_InstaniateMediaPlayer; // 0x0
	private static DelegateBridge __Hotfix0_CheckVideoExist; // 0x8
	private static DelegateBridge __Hotfix0_GetVideoFullPath; // 0x10
	private static DelegateBridge __Hotfix0_TreatVideoPath; // 0x18
	private static DelegateBridge __Hotfix0_IsMp4VideoPath; // 0x20
	private static DelegateBridge __Hotfix0_OnInitSDK; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3727dd4 VA: 0x7595d3fdd4
	public AbstractMediaPlayerHolder InstaniateMediaPlayer(Transform container) { }
	// RVA: 0x3727eb4 VA: 0x7595d3feb4
	public Boolean CheckVideoExist(String path) { }
	// RVA: 0x3727fb8 VA: 0x7595d3ffb8
	public String GetVideoFullPath(String path) { }
	// RVA: 0x3727f3c VA: 0x7595d3ff3c
	public String TreatVideoPath(String path) { }
	// RVA: 0x3728044 VA: 0x7595d40044
	public Boolean IsMp4VideoPath(String path) { }
	// RVA: 0x37280e4 VA: 0x7595d400e4
	public Void OnInitSDK(Boolean isInitScene) { }
	// RVA: 0x3728270 VA: 0x7595d40270
	public Void .ctor() { }
}
```