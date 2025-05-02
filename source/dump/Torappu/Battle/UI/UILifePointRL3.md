# UILifePointRL3

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _tweenTime`

- `UIAtlasImage _lifePointMask`

- `Int32 m_lifePoint`


## Methods

- `Void SetData(Int32)`

- `Void UpdateData(Int32)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILifePointRL3 : MonoBehaviour
{
	private Single _tweenTime; // 0x18
	private Image[] _images; // 0x20
	protected UIAtlasImage _lifePointMask; // 0x28
	private Int32 m_lifePoint; // 0x30


	// RVA: 0x2070fec VA: 0x7594688fec
	public Void SetData(Int32 lifePoint) { }
	// RVA: 0x20710d0 VA: 0x75946890d0
	public Void UpdateData(Int32 lifePoint) { }
	// RVA: 0x2071354 VA: 0x7594689354
	private Void OnDestroy() { }
	// RVA: 0x207142c VA: 0x759468942c
	public Void .ctor() { }
}
```