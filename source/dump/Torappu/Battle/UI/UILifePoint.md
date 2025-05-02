# UILifePoint

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _lifePointLabel`

- `Single _tweenTime`

- `Int32 m_lifePoint`


## Methods

- `Void SetData(Int32)`

- `Void UpdateData(Int32)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILifePoint : MonoBehaviour, IHotfixable
{
	private Text _lifePointLabel; // 0x18
	private Single _tweenTime; // 0x20
	private Image[] _images; // 0x28
	private Int32 m_lifePoint; // 0x30
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x20816f8 VA: 0x75946996f8
	public Void SetData(Int32 lifePoint) { }
	// RVA: 0x2077720 VA: 0x759468f720
	public Void UpdateData(Int32 lifePoint) { }
	// RVA: 0x2081858 VA: 0x7594699858
	private Void OnDestroy() { }
	// RVA: 0x2081960 VA: 0x7594699960
	public Void .ctor() { }
}
```