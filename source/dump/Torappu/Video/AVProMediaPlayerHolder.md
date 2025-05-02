# AVProMediaPlayerHolder

**Namespace:** `Torappu.Video`


## Fields

- `MediaPlayer _mediaPlayer`

- `Status m_cacheStatus`


## Methods

- `Status _TweenStatus(EventType)`

- `Void _HandlePlayEvent(MediaPlayer, EventType, ErrorCode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Video
public class AVProMediaPlayerHolder : AbstractMediaPlayerHolder
{
	private MediaPlayer _mediaPlayer; // 0x18
	private Action`1 m_handlerAction; // 0x20
	private Status m_cacheStatus; // 0x28
	private static DelegateBridge __Hotfix0_AddListener; // 0x0
	private static DelegateBridge __Hotfix0_GetCurrentStatus; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_IsAbleToPlay; // 0x18
	private static DelegateBridge __Hotfix0_Play; // 0x20
	private static DelegateBridge __Hotfix0_RemoveListener; // 0x28
	private static DelegateBridge __Hotfix0_SetPath; // 0x30
	private static DelegateBridge __Hotfix0_SetVolume; // 0x38
	private static DelegateBridge __Hotfix0_Stop; // 0x40
	private static DelegateBridge __Hotfix0__TweenStatus; // 0x48
	private static DelegateBridge __Hotfix0__HandlePlayEvent; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x372743c VA: 0x7595d3f43c
	public override Void AddListener(Action`1 onReadyEvent) { }
	// RVA: 0x3727524 VA: 0x7595d3f524
	public override Status GetCurrentStatus() { }
	// RVA: 0x372758c VA: 0x7595d3f58c
	public override Void Init() { }
	// RVA: 0x3727664 VA: 0x7595d3f664
	public override Boolean IsAbleToPlay() { }
	// RVA: 0x37277f4 VA: 0x7595d3f7f4
	public override Void Play() { }
	// RVA: 0x3727868 VA: 0x7595d3f868
	public override Void RemoveListener(Action`1 onReadyEvent) { }
	// RVA: 0x3727950 VA: 0x7595d3f950
	protected override Void SetPath(String path) { }
	// RVA: 0x37279e4 VA: 0x7595d3f9e4
	public override Void SetVolume(Single volume) { }
	// RVA: 0x3727a6c VA: 0x7595d3fa6c
	public override Void Stop() { }
	// RVA: 0x3727ae0 VA: 0x7595d3fae0
	private Status _TweenStatus(EventType status) { }
	// RVA: 0x3727b78 VA: 0x7595d3fb78
	private Void _HandlePlayEvent(MediaPlayer player, EventType evt, ErrorCode error) { }
	// RVA: 0x3727cf0 VA: 0x7595d3fcf0
	public Void .ctor() { }
}
```