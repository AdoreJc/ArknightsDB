# HandbookSixLineView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Vector3 _initPos`


## Methods

- `Void Init(String)`

- `Void OnValueChanged(HandBookScrollViewProperty)`

- `Void SetLineState(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandbookSixLineView : MonoBehaviour
{
	private Image[] _sixLine; // 0x18
	private Sprite[] _sixLineSprite; // 0x20
	public Vector3 _initPos; // 0x28


	// RVA: 0x2eb4a20 VA: 0x75954cca20
	public Void Init(String powerId) { }
	// RVA: 0x2eb52b0 VA: 0x75954cd2b0
	public Void OnValueChanged(HandBookScrollViewProperty property) { }
	// RVA: 0x2eb4b2c VA: 0x75954ccb2c
	public Void SetLineState(Int32 id, Int32 state) { }
	// RVA: 0x2eb65e0 VA: 0x75954ce5e0
	public Void .ctor() { }
}
```