# SandboxV2LogisticsCharBeanView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2LogisticsAbstractBeanItem _panelBeanPrefab`

- `Single _itemScale`

- `Int32 m_cachedTotalBeanCount`

- `Int32 m_cachedCurrentBeanCount`


## Methods

- `Void Render(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsCharBeanView : MonoBehaviour, IHotfixable
{
	private SandboxV2LogisticsAbstractBeanItem _panelBeanPrefab; // 0x18
	private Single _itemScale; // 0x20
	private Int32 m_cachedTotalBeanCount; // 0x24
	private Int32 m_cachedCurrentBeanCount; // 0x28
	private List`1 m_itemList; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25db2e4 VA: 0x7594bf32e4
	public Void Render(Int32 totalCount, Int32 currentCount) { }
	// RVA: 0x25db588 VA: 0x7594bf3588
	public Void .ctor() { }
}
```