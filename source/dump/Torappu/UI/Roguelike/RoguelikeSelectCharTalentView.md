# RoguelikeSelectCharTalentView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _descText`

- `SimpleLayoutContent _content`

- `GameObject _titlePart`

- `LayoutElement _layoutElement`

- `GameObject _hideBtn`

- `GameObject _showBtn`

- `Adapter m_adapter`

- `Boolean isHide`

- `Tween m_cacheTween`

- `Boolean m_isInited`


## Methods

- `Void RenderOnFirstTime()`

- `Void _InitIfNot()`

- `Void Render(RoguelikeCharCardViewModel)`

- `Void OnHide()`

- `Void OnShow()`

- `Single <OnHide>b__14_0()`

- `Void <OnHide>b__14_1(Single)`

- `Void <OnHide>b__14_2()`

- `Single <OnShow>b__15_0()`

- `Void <OnShow>b__15_1(Single)`

- `Void <OnShow>b__15_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSelectCharTalentView : MonoBehaviour, IHotfixable
{
	private Text _descText; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private GameObject _titlePart; // 0x28
	private LayoutElement _layoutElement; // 0x30
	private GameObject _hideBtn; // 0x38
	private GameObject _showBtn; // 0x40
	private Adapter m_adapter; // 0x48
	private Boolean isHide; // 0x50
	private Tween m_cacheTween; // 0x58
	private Boolean m_isInited; // 0x60
	private const Single MIN_HEIGHT; // 0x0
	private static DelegateBridge __Hotfix0_RenderOnFirstTime; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnHide; // 0x18
	private static DelegateBridge __Hotfix0_OnShow; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2acfeec VA: 0x75950e7eec
	public Void RenderOnFirstTime() { }
	// RVA: 0x2acff94 VA: 0x75950e7f94
	private Void _InitIfNot() { }
	// RVA: 0x2ad00d0 VA: 0x75950e80d0
	public Void Render(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2ad0474 VA: 0x75950e8474
	public Void OnHide() { }
	// RVA: 0x2ad06c4 VA: 0x75950e86c4
	public Void OnShow() { }
	// RVA: 0x2ad0904 VA: 0x75950e8904
	public Void .ctor() { }
	// RVA: 0x2ad0974 VA: 0x75950e8974
	private Single <OnHide>b__14_0() { }
	// RVA: 0x2ad0998 VA: 0x75950e8998
	private Void <OnHide>b__14_1(Single val) { }
	// RVA: 0x2ad09bc VA: 0x75950e89bc
	private Void <OnHide>b__14_2() { }
	// RVA: 0x2ad09cc VA: 0x75950e89cc
	private Single <OnShow>b__15_0() { }
	// RVA: 0x2ad09f0 VA: 0x75950e89f0
	private Void <OnShow>b__15_1(Single val) { }
	// RVA: 0x2ad0a14 VA: 0x75950e8a14
	private Void <OnShow>b__15_2() { }
}
```