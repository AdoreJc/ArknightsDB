# SofdecMediaPlayer

**Namespace:** `Torappu.Video`


## Fields

- `CriManaMovieControllerForUI _moviePlayer`

- `RectTransform _rect`

- `RectTransform _holder`


## Methods

- `Status _TweenStatus(Status)`

- `Void OnStatusChanged(Status)`


## Dump
```C#
// Dll : Torappu.Sofdec.dll
// Namespace : Torappu.Video
public class SofdecMediaPlayer : AbstractMediaPlayerHolder
{
	private CriManaMovieControllerForUI _moviePlayer; // 0x18
	private RectTransform _rect; // 0x20
	private RectTransform _holder; // 0x28
	private Action`1 m_handlerAction; // 0x30
	private static __XLua_Gen_Delegate0 __Hotfix0_AddListener; // 0x0
	private static __XLua_Gen_Delegate0 __Hotfix0_RemoveListener; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_Init; // 0x10
	private static __XLua_Gen_Delegate2 __Hotfix0_IsAbleToPlay; // 0x18
	private static __XLua_Gen_Delegate1 __Hotfix0_Play; // 0x20
	private static __XLua_Gen_Delegate3 __Hotfix0__TweenStatus; // 0x28
	private static __XLua_Gen_Delegate4 __Hotfix0_OnStatusChanged; // 0x30
	private static __XLua_Gen_Delegate0 __Hotfix0_SetPath; // 0x38
	private static __XLua_Gen_Delegate5 __Hotfix0_GetCurrentStatus; // 0x40
	private static __XLua_Gen_Delegate6 __Hotfix0_SetVolume; // 0x48
	private static __XLua_Gen_Delegate1 __Hotfix0_Stop; // 0x50
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x58


	// RVA: 0x67d1c58 VA: 0x7598de9c58
	public override Void AddListener(Action`1 statusChangeEvent) { }
	// RVA: 0x67d1d48 VA: 0x7598de9d48
	public override Void RemoveListener(Action`1 statusChangeEvent) { }
	// RVA: 0x67d1e38 VA: 0x7598de9e38
	public override Void Init() { }
	// RVA: 0x67d1f7c VA: 0x7598de9f7c
	public override Boolean IsAbleToPlay() { }
	// RVA: 0x67d200c VA: 0x7598dea00c
	public override Void Play() { }
	// RVA: 0x67d21a0 VA: 0x7598dea1a0
	private Status _TweenStatus(Status status) { }
	// RVA: 0x67d223c VA: 0x7598dea23c
	private Void OnStatusChanged(Status status) { }
	// RVA: 0x67d22f0 VA: 0x7598dea2f0
	protected override Void SetPath(String path) { }
	// RVA: 0x67d23ac VA: 0x7598dea3ac
	public override Status GetCurrentStatus() { }
	// RVA: 0x67d243c VA: 0x7598dea43c
	public override Void SetVolume(Single volume) { }
	// RVA: 0x67d24d8 VA: 0x7598dea4d8
	public override Void Stop() { }
	// RVA: 0x67d2554 VA: 0x7598dea554
	public Void .ctor() { }
}
```