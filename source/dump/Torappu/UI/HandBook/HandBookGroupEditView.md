# HandBookGroupEditView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapPosDB _posDB`

- `HandBookGroupDetailEdit _edit`

- `InputField _inputField`

- `TextAsset _textAssets`

- `HandBookV2MapPosData posData`


## Methods

- `Void Start()`

- `Void OnShow()`

- `String CheckIsNPCAvail(String)`

- `Void SaveData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookGroupEditView : MonoBehaviour
{
	private Dictionary`2 m_npcPair; // 0x18
	private HandBookV2MapPosDB _posDB; // 0x20
	private HandBookGroupDetailEdit _edit; // 0x28
	private InputField _inputField; // 0x30
	private TextAsset _textAssets; // 0x38
	public HandBookV2MapPosData posData; // 0x40

	public Dictionary`2 npcPair { get; }

	// RVA: 0x2ec463c VA: 0x75954dc63c
	public Dictionary`2 get_npcPair() { }
	// RVA: 0x2ec475c VA: 0x75954dc75c
	private Void Start() { }
	// RVA: 0x2ec4958 VA: 0x75954dc958
	public Void OnShow() { }
	// RVA: 0x2ec4a74 VA: 0x75954dca74
	public String CheckIsNPCAvail(String charId) { }
	// RVA: 0x2ec4b2c VA: 0x75954dcb2c
	public Void SaveData() { }
	// RVA: 0x2ec4b30 VA: 0x75954dcb30
	public Void .ctor() { }
}
```