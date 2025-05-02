# StageMixStoryRetroLineView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `GameObject _continuousPanel`

- `GameObject _discretePanel`

- `StageMixStoryRetroLineItemView _itemPrefab`

- `Transform _itemParent`

- `Int32 _activeDistance`

- `Ease _focusEase`

- `Boolean m_hasInited`

- `Animator m_animator`

- `Int32 m_cachedPosition`


## Methods

- `Void ResetView()`

- `Void Render(MixStoryZoneGroupViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryRetroLineView : MonoBehaviour, IHotfixable
{
	private GameObject _continuousPanel; // 0x18
	private GameObject _discretePanel; // 0x20
	private StageMixStoryRetroLineItemView _itemPrefab; // 0x28
	private Transform _itemParent; // 0x30
	private Int32 _activeDistance; // 0x38
	private Ease _focusEase; // 0x3c
	private Boolean m_hasInited; // 0x40
	private Animator m_animator; // 0x48
	private Int32 m_cachedPosition; // 0x50
	private static DelegateBridge __Hotfix0_ResetView; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fff2c0 VA: 0x75956172c0
	public Void ResetView() { }
	// RVA: 0x2fff32c VA: 0x759561732c
	public Void Render(MixStoryZoneGroupViewModel model) { }
	// RVA: 0x2fff460 VA: 0x7595617460
	private Void _InitIfNot() { }
	// RVA: 0x2fff8ac VA: 0x75956178ac
	public Void .ctor() { }
}
```