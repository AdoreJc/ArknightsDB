# HandBookGroupDetailEdit

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookGroupCharEdit _edit`

- `HandBookForceLogoEdit _logoEdit`

- `HandBookV2ColorBlockEdit _colorEdit`

- `Transform _container`

- `InputField _charNameInputField`

- `InputField _forceIdInputField`

- `HandBookV2MapLineView _lineView`

- `Transform _lineContainer`

- `SimpleLayoutContent _forceContent`

- `UIStringEvent _onClick`

- `UIStringEvent _onFocusView`

- `UIStringEvent _onSaveFocusView`

- `UIStringEvent _onDeleteForce`

- `RectTransform _scrollContainer`

- `HandBookGroupForceEditAdapter m_adapter`

- `Single _lineLength`

- `HandBookV2GroupPosData m_cacheData`

- `Int32 lineMaxInt`


## Properties

- `HandBookV2GroupPosData cacheData`


## Methods

- `Void init()`

- `HandBookV2GroupPosData get_cacheData()`

- `Void RenderForce()`

- `Void RenderLine()`

- `Void Render(HandBookV2GroupPosData)`

- `Void _CheckCard(HandBookGroupCommonPosEdit, out, out)`

- `Void RemovePos(HandBookGroupCommonPosEdit)`

- `Void CheckPos(HandBookGroupCommonPosEdit)`

- `Void InstNewForce()`

- `Void InstantiateNewChar()`

- `Void DeleteSelectChar()`

- `Void CheckPosConnection(Int32, Int32, List`1)`

- `Void CheckConnection()`

- `Void RenderForceColor()`

- `Void FocusForce(String)`

- `Void SaveFocusForce(String)`

- `Void AddForceColorBar(String)`

- `Void DeleteForce(String)`

- `Void SetForce(String)`

- `Void LargeSize()`

- `Void SmallSize()`

- `Void NormalSize()`

- `Void RemoveLine()`

- `Void AddLine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookGroupDetailEdit : MonoBehaviour
{
	public static HandBookGroupDetailEdit instance; // 0x0
	private HandBookGroupCharEdit _edit; // 0x18
	private HandBookForceLogoEdit _logoEdit; // 0x20
	private HandBookV2ColorBlockEdit _colorEdit; // 0x28
	private Transform _container; // 0x30
	private InputField _charNameInputField; // 0x38
	private InputField _forceIdInputField; // 0x40
	private HandBookV2MapLineView _lineView; // 0x48
	private Transform _lineContainer; // 0x50
	private SimpleLayoutContent _forceContent; // 0x58
	private UIStringEvent _onClick; // 0x60
	private UIStringEvent _onFocusView; // 0x68
	private UIStringEvent _onSaveFocusView; // 0x70
	private UIStringEvent _onDeleteForce; // 0x78
	private RectTransform _scrollContainer; // 0x80
	private HandBookGroupForceEditAdapter m_adapter; // 0x88
	public Single _lineLength; // 0x90
	public Dictionary`2 charList; // 0x98
	public Dictionary`2 colorBarList; // 0xa0
	public Dictionary`2 forceLogoList; // 0xa8
	public List`1 onSelectChar; // 0xb0
	public Dictionary`2 charMap; // 0xb8
	private HandBookV2GroupPosData m_cacheData; // 0xc0
	public Int32 lineMaxInt; // 0xc8

	public HandBookV2GroupPosData cacheData { get; }

	// RVA: 0x2ec18bc VA: 0x75954d98bc
	private Void init() { }
	// RVA: 0x2ec1a30 VA: 0x75954d9a30
	public HandBookV2GroupPosData get_cacheData() { }
	// RVA: 0x2ec1a38 VA: 0x75954d9a38
	public Void RenderForce() { }
	// RVA: 0x2ec1470 VA: 0x75954d9470
	public Void RenderLine() { }
	// RVA: 0x2ec1bcc VA: 0x75954d9bcc
	public Void Render(HandBookV2GroupPosData posData) { }
	// RVA: 0x2ec2044 VA: 0x75954da044
	private Void _CheckCard(HandBookGroupCommonPosEdit card, out Int32 x, out Int32 y) { }
	// RVA: 0x2ec2380 VA: 0x75954da380
	public Void RemovePos(HandBookGroupCommonPosEdit card) { }
	// RVA: 0x2ec1698 VA: 0x75954d9698
	public Void CheckPos(HandBookGroupCommonPosEdit card) { }
	// RVA: 0x2ec2470 VA: 0x75954da470
	public Void InstNewForce() { }
	// RVA: 0x2ec260c VA: 0x75954da60c
	public Void InstantiateNewChar() { }
	// RVA: 0x2ec2818 VA: 0x75954da818
	public Void DeleteSelectChar() { }
	// RVA: 0x2ec2be8 VA: 0x75954dabe8
	public static Vector2 GetConnectHexagonDirectionPos(HexagonDirection direction) { }
	// RVA: 0x2ec2cfc VA: 0x75954dacfc
	public Void CheckPosConnection(Int32 x, Int32 y, List`1 connectionList) { }
	// RVA: 0x2ec30a4 VA: 0x75954db0a4
	public Void CheckConnection() { }
	// RVA: 0x2ec1d44 VA: 0x75954d9d44
	public Void RenderForceColor() { }
	// RVA: 0x2ec34f0 VA: 0x75954db4f0
	public Void FocusForce(String forceId) { }
	// RVA: 0x2ec35b4 VA: 0x75954db5b4
	public Void SaveFocusForce(String forceId) { }
	// RVA: 0x2ec3678 VA: 0x75954db678
	public Void AddForceColorBar(String forceId) { }
	// RVA: 0x2ec3a60 VA: 0x75954dba60
	public Void DeleteForce(String forceId) { }
	// RVA: 0x2ec3b44 VA: 0x75954dbb44
	public Void SetForce(String forceId) { }
	// RVA: 0x2ec3db4 VA: 0x75954dbdb4
	public Void LargeSize() { }
	// RVA: 0x2ec3e88 VA: 0x75954dbe88
	public Void SmallSize() { }
	// RVA: 0x2ec3f5c VA: 0x75954dbf5c
	public Void NormalSize() { }
	// RVA: 0x2ec4030 VA: 0x75954dc030
	public Void RemoveLine() { }
	// RVA: 0x2ec414c VA: 0x75954dc14c
	public Void AddLine() { }
	// RVA: 0x2ec4460 VA: 0x75954dc460
	public Void .ctor() { }
}
```