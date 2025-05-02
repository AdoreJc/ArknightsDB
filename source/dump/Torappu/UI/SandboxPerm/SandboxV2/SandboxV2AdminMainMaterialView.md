# SandboxV2AdminMainMaterialView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _iconImage`

- `Text _countText`

- `Single _validAlpha`

- `Single _invalidAlpha`

- `Color _validCountColor`

- `Color _invalidCountColor`

- `Boolean m_hasInited`

- `UIStateFinder m_finder`

- `String m_cachedId`


## Methods

- `Void Render(String, SandboxV2AdminMainMaterialModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainMaterialView : MonoBehaviour, IHotfixable
{
	private Image _iconImage; // 0x18
	private Text _countText; // 0x20
	private List`1 _colorConfigs; // 0x28
	private Single _validAlpha; // 0x30
	private Single _invalidAlpha; // 0x34
	private Color _validCountColor; // 0x38
	private Color _invalidCountColor; // 0x48
	private Boolean m_hasInited; // 0x58
	private readonly Dictionary`2 m_colorOfTypes; // 0x60
	private UIStateFinder m_finder; // 0x68
	private String m_cachedId; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24baf6c VA: 0x7594ad2f6c
	public Void Render(String topicId, SandboxV2AdminMainMaterialModel model) { }
	// RVA: 0x24bb2d8 VA: 0x7594ad32d8
	private Void _InitIfNot() { }
	// RVA: 0x24bb400 VA: 0x7594ad3400
	public Void .ctor() { }
}
```