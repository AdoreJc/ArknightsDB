# RecruitSpecialCharPortGroupView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `SimpleLayoutContent _content`

- `Image _imgStarIcon`

- `GameObject _panelSplitLine`

- `Text _textTitle`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `JArrayWrapper m_cachedCharIdList`


## Methods

- `Void Render(Input)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialCharPortGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Image _imgStarIcon; // 0x20
	private GameObject _panelSplitLine; // 0x28
	private Text _textTitle; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private JArrayWrapper m_cachedCharIdList; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27111a0 VA: 0x7594d291a0
	public Void Render(Input input) { }
	// RVA: 0x27112b8 VA: 0x7594d292b8
	private Void _InitIfNot() { }
	// RVA: 0x271141c VA: 0x7594d2941c
	public Void .ctor() { }
}
```