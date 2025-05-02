# CharacterInfoRightProfSpreadView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `SimpleLayoutContent _content`

- `Single _initHeight`

- `TalentAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Single CalcHeight()`

- `Void Render(CharViewModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightProfSpreadView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private List`1 _objList; // 0x20
	private Single _initHeight; // 0x28
	private TalentAdapter m_adapter; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_CalcHeight; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d831cc VA: 0x759539b1cc
	private Void _InitIfNot() { }
	// RVA: 0x2d83308 VA: 0x759539b308
	public Single CalcHeight() { }
	// RVA: 0x2d835f0 VA: 0x759539b5f0
	public Void Render(CharViewModel viewModel, Int32 equipScrollSequenceNum) { }
	// RVA: 0x2d838f0 VA: 0x759539b8f0
	public Void .ctor() { }
}
```