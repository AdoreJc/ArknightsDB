# SandboxV2GainItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `AnimationWrapper _animationWrapper`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Tween m_cachedEnterAnim`


## Properties

- `Boolean isEnterAnimPlaying`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Boolean get_isEnterAnimPlaying()`

- `Void Render(IList`1)`

- `GameObject TipOnlyGetItemCardGo(Int32)`

- `Void PlayRewardAudio()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2GainItemView : MonoBehaviour, IHotfixable
{
	private const String ENTER_ANIM_KEY; // 0x0
	private SimpleLayoutContent _content; // 0x18
	private AnimationWrapper _animationWrapper; // 0x20
	private Boolean m_hasInited; // 0x28
	private IList`1 m_cachedItemList; // 0x30
	private Adapter m_adapter; // 0x38
	private Tween m_cachedEnterAnim; // 0x40
	private Action`1 <onItemClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_isEnterAnimPlaying; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_TipOnlyGetItemCardGo; // 0x20
	private static DelegateBridge __Hotfix0_PlayRewardAudio; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 onItemClicked { get; set; }
	public Boolean isEnterAnimPlaying { get; }

	// RVA: 0x25c9f98 VA: 0x7594be1f98
	private Action`1 get_onItemClicked() { }
	// RVA: 0x25c8824 VA: 0x7594be0824
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x25c8bb4 VA: 0x7594be0bb4
	public Boolean get_isEnterAnimPlaying() { }
	// RVA: 0x25c88a8 VA: 0x7594be08a8
	public Void Render(IList`1 itemModels) { }
	// RVA: 0x25c8d7c VA: 0x7594be0d7c
	public GameObject TipOnlyGetItemCardGo(Int32 index) { }
	// RVA: 0x25ca0e4 VA: 0x7594be20e4
	public Void PlayRewardAudio() { }
	// RVA: 0x25ca000 VA: 0x7594be2000
	private Void _InitIfNot() { }
	// RVA: 0x25ca220 VA: 0x7594be2220
	public Void .ctor() { }
}
```