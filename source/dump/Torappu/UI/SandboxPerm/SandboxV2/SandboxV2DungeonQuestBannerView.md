# SandboxV2DungeonQuestBannerView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _questNameText`

- `UIAtlasImage _questIconImg`

- `UIAnimationLocation _enterAnim`

- `Param m_param`

- `Action <onBannerQuit>k__BackingField`


## Properties

- `Action onBannerQuit`


## Methods

- `Action get_onBannerQuit()`

- `Void set_onBannerQuit(Action)`

- `Void SetParam(Param)`

- `Void Render(ViewModel)`

- `Void _PlayEnterAnim()`

- `Void PlayQuestStartAudio()`

- `Void PlayQuestFailAudio()`

- `Void PlayQuestCompletedAudio()`

- `Void <_PlayEnterAnim>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonQuestBannerView : MonoBehaviour, IHotfixable
{
	private Text _questNameText; // 0x18
	private UIAtlasImage _questIconImg; // 0x20
	private UIAnimationLocation _enterAnim; // 0x28
	private Param m_param; // 0x38
	private Action <onBannerQuit>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onBannerQuit; // 0x0
	private static DelegateBridge __Hotfix0_set_onBannerQuit; // 0x8
	private static DelegateBridge __Hotfix0_SetParam; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0_PlayQuestStartAudio; // 0x28
	private static DelegateBridge __Hotfix0_PlayQuestFailAudio; // 0x30
	private static DelegateBridge __Hotfix0_PlayQuestCompletedAudio; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action onBannerQuit { get; set; }

	// RVA: 0x255bc40 VA: 0x7594b73c40
	private Action get_onBannerQuit() { }
	// RVA: 0x255bca8 VA: 0x7594b73ca8
	public Void set_onBannerQuit(Action value) { }
	// RVA: 0x255bd2c VA: 0x7594b73d2c
	public Void SetParam(Param param) { }
	// RVA: 0x255bdb0 VA: 0x7594b73db0
	public Void Render(ViewModel viewModel) { }
	// RVA: 0x255bedc VA: 0x7594b73edc
	private Void _PlayEnterAnim() { }
	// RVA: 0x255c000 VA: 0x7594b74000
	public Void PlayQuestStartAudio() { }
	// RVA: 0x255c0a8 VA: 0x7594b740a8
	public Void PlayQuestFailAudio() { }
	// RVA: 0x255c150 VA: 0x7594b74150
	public Void PlayQuestCompletedAudio() { }
	// RVA: 0x255c1f8 VA: 0x7594b741f8
	public Void .ctor() { }
	// RVA: 0x255c268 VA: 0x7594b74268
	private Void <_PlayEnterAnim>b__12_0() { }
}
```