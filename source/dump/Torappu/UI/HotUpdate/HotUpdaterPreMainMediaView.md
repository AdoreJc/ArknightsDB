# HotUpdaterPreMainMediaView

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Transform _mediaPlayerContainer`

- `AbstractMediaPlayerHolder m_mediaPlayer`

- `Boolean m_isInited`

- `AudioChannelEffect m_audioChannelEffect`


## Methods

- `Void _InitIfNot()`

- `AudioChannelEffect _GenerateMuteAudioChannelEffect()`

- `Void OnApplicationPause(Boolean)`

- `Void _HandlePlayEvent(Status)`

- `Void OnPvPlayEnd()`

- `Void _ApplyMusicSettings()`

- `Void <>xLuaBaseProxy_Render(HotUpdatePremainViewModel, IAssets)`

- `IEnumerator <>xLuaBaseProxy_Show(PreMainState)`

- `Void <>xLuaBaseProxy_Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdaterPreMainMediaView : AbstractHotUpdatePreMainFadeInView
{
	private Transform _mediaPlayerContainer; // 0x48
	private AbstractMediaPlayerHolder m_mediaPlayer; // 0x50
	private Boolean m_isInited; // 0x58
	private AudioChannelEffect m_audioChannelEffect; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_state; // 0x8
	private static DelegateBridge __Hotfix0__GenerateMuteAudioChannelEffect; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_Show; // 0x20
	private static DelegateBridge __Hotfix0_OnApplicationPause; // 0x28
	private static DelegateBridge __Hotfix0_Clear; // 0x30
	private static DelegateBridge __Hotfix0__HandlePlayEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnPvPlayEnd; // 0x40
	private static DelegateBridge __Hotfix0__ApplyMusicSettings; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected override PreMainState state { get; }

	// RVA: 0x27cbbdc VA: 0x7594de3bdc
	private Void _InitIfNot() { }
	// RVA: 0x27cbc98 VA: 0x7594de3c98
	protected override PreMainState get_state() { }
	// RVA: 0x27cbd00 VA: 0x7594de3d00
	private AudioChannelEffect _GenerateMuteAudioChannelEffect() { }
	// RVA: 0x27cbf5c VA: 0x7594de3f5c
	public override Void Render(HotUpdatePremainViewModel viewModel, IAssets assets) { }
	// RVA: 0x27cc2f8 VA: 0x7594de42f8
	public override IEnumerator Show(PreMainState lastState) { }
	// RVA: 0x27cc3e4 VA: 0x7594de43e4
	private Void OnApplicationPause(Boolean pauseStatus) { }
	// RVA: 0x27cc50c VA: 0x7594de450c
	public override Void Clear() { }
	// RVA: 0x27cc67c VA: 0x7594de467c
	private Void _HandlePlayEvent(Status evt) { }
	// RVA: 0x27cc140 VA: 0x7594de4140
	public Void OnPvPlayEnd() { }
	// RVA: 0x27cc254 VA: 0x7594de4254
	private Void _ApplyMusicSettings() { }
	// RVA: 0x27cc83c VA: 0x7594de483c
	public Void .ctor() { }
	// RVA: 0x27cc8a8 VA: 0x7594de48a8
	private Void <>xLuaBaseProxy_Render(HotUpdatePremainViewModel P0, IAssets P1) { }
	// RVA: 0x27cc8ac VA: 0x7594de48ac
	private IEnumerator <>xLuaBaseProxy_Show(PreMainState P0) { }
	// RVA: 0x27cc8b0 VA: 0x7594de48b0
	private Void <>xLuaBaseProxy_Clear() { }
}
```