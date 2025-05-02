# MedalListTitleView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _backImage`

- `Image _titleImage`

- `GameObject _container`

- `GameObject _emptyState`

- `UIStringEvent clickToGroupEvent`

- `MedalGroupViewModel m_cacheViewModel`


## Methods

- `Void RenderTitle(MedalGroupViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListTitleView : MonoBehaviour, IHotfixable
{
	private Image _backImage; // 0x18
	private Image _titleImage; // 0x20
	private GameObject _container; // 0x28
	private GameObject _emptyState; // 0x30
	public UIStringEvent clickToGroupEvent; // 0x38
	private MedalGroupViewModel m_cacheViewModel; // 0x40
	private static DelegateBridge __Hotfix0_RenderTitle; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27a3cd0 VA: 0x7594dbbcd0
	public Void RenderTitle(MedalGroupViewModel groupViewModel) { }
	// RVA: 0x27a3ef0 VA: 0x7594dbbef0
	public Void OnClick() { }
	// RVA: 0x27a3f94 VA: 0x7594dbbf94
	public Void .ctor() { }
}
```