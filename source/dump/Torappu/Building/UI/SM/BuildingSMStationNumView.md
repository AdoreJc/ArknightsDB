# BuildingSMStationNumView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Color _disableColor`

- `Color _hilightColor`

- `Color _normalColor`

- `Text m_text`

- `Int32 m_num`

- `Int32 m_limit`

- `Boolean m_isInited`

- `StringBuilder m_sharedBuilder`


## Properties

- `Text text`


## Methods

- `Text get_text()`

- `Void Render(Int32, Int32)`

- `String _MakeRichNumber(Int32, Color, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMStationNumView : MonoBehaviour, IHotfixable
{
	private Color _disableColor; // 0x18
	private Color _hilightColor; // 0x28
	private Color _normalColor; // 0x38
	private Text m_text; // 0x48
	private Int32 m_num; // 0x50
	private Int32 m_limit; // 0x54
	private Boolean m_isInited; // 0x58
	private StringBuilder m_sharedBuilder; // 0x60
	private static DelegateBridge __Hotfix0_get_text; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__MakeRichNumber; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Text text { get; }

	// RVA: 0x3db077c VA: 0x75963c877c
	public Text get_text() { }
	// RVA: 0x3db0854 VA: 0x75963c8854
	public Void Render(Int32 num, Int32 limit) { }
	// RVA: 0x3db0a7c VA: 0x75963c8a7c
	private String _MakeRichNumber(Int32 num, Color zeroColor, Color otherColor) { }
	// RVA: 0x3db0cdc VA: 0x75963c8cdc
	public Void .ctor() { }
}
```