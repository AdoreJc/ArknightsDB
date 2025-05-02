# HotUpdaterPreMainPicView

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Image _backImage`

- `Image _logoImg`

- `SimpleLayoutContent _textContent`

- `GameObject _replayBtn`

- `GameObject _skinIcon`

- `String m_cachePicId`

- `IEnumerator m_tweenCoroutine`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void PlayTargetPic(PicInfo, IAssets)`

- `IEnumerator _PlayPicChange(PicInfo, IAssets)`

- `Void _RenderView(PicInfo, IAssets)`

- `Void ClearCacheImage()`

- `Void OnPvPlay()`

- `Boolean <>xLuaBaseProxy_IsShow(HotUpdatePremainViewModel)`

- `Void <>xLuaBaseProxy_Render(HotUpdatePremainViewModel, IAssets)`

- `Void <>xLuaBaseProxy_Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdaterPreMainPicView : AbstractHotUpdatePreMainFadeInView
{
	private Image _backImage; // 0x48
	private Image _logoImg; // 0x50
	private SimpleLayoutContent _textContent; // 0x58
	private GameObject _replayBtn; // 0x60
	private GameObject _skinIcon; // 0x68
	private String m_cachePicId; // 0x70
	private IEnumerator m_tweenCoroutine; // 0x78
	private Adapter m_adapter; // 0x80
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_IsShow; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_Clear; // 0x20
	private static DelegateBridge __Hotfix0_PlayTargetPic; // 0x28
	private static DelegateBridge __Hotfix0__PlayPicChange; // 0x30
	private static DelegateBridge __Hotfix0__RenderView; // 0x38
	private static DelegateBridge __Hotfix0_ClearCacheImage; // 0x40
	private static DelegateBridge __Hotfix0_OnPvPlay; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected override PreMainState state { get; }

	// RVA: 0x27cca28 VA: 0x7594de4a28
	protected override PreMainState get_state() { }
	// RVA: 0x27cca90 VA: 0x7594de4a90
	private Void _InitIfNot() { }
	// RVA: 0x27ccb5c VA: 0x7594de4b5c
	protected override Boolean IsShow(HotUpdatePremainViewModel viewModel) { }
	// RVA: 0x27ccc20 VA: 0x7594de4c20
	public override Void Render(HotUpdatePremainViewModel viewModel, IAssets assets) { }
	// RVA: 0x27ccf60 VA: 0x7594de4f60
	public override Void Clear() { }
	// RVA: 0x27ccd48 VA: 0x7594de4d48
	public Void PlayTargetPic(PicInfo picInfo, IAssets assets) { }
	// RVA: 0x27cd05c VA: 0x7594de505c
	private IEnumerator _PlayPicChange(PicInfo picInfo, IAssets assets) { }
	// RVA: 0x27cd144 VA: 0x7594de5144
	private Void _RenderView(PicInfo picInfo, IAssets assets) { }
	// RVA: 0x27ccfd0 VA: 0x7594de4fd0
	public Void ClearCacheImage() { }
	// RVA: 0x27cd3b4 VA: 0x7594de53b4
	public Void OnPvPlay() { }
	// RVA: 0x27cd4a4 VA: 0x7594de54a4
	public Void .ctor() { }
	// RVA: 0x27cd510 VA: 0x7594de5510
	private Boolean <>xLuaBaseProxy_IsShow(HotUpdatePremainViewModel P0) { }
	// RVA: 0x27cd514 VA: 0x7594de5514
	private Void <>xLuaBaseProxy_Render(HotUpdatePremainViewModel P0, IAssets P1) { }
	// RVA: 0x27cd518 VA: 0x7594de5518
	private Void <>xLuaBaseProxy_Clear() { }
}
```