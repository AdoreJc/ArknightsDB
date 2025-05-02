# WeeklyGroupZoneIconWidget

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _iconActive`

- `Sprite _iconInactive`

- `Sprite _iconForceOpen`

- `Sprite _iconForceOpenToday`


## Methods

- `Vector2 GetIconPos(GameDayOfWeek)`

- `Void Render(WeekStruct`1, GetOpenState`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class WeeklyGroupZoneIconWidget : MonoBehaviour, IHotfixable
{
	private Image[] _iconList; // 0x18
	private Sprite _iconActive; // 0x20
	private Sprite _iconInactive; // 0x28
	private Sprite _iconForceOpen; // 0x30
	private Sprite _iconForceOpenToday; // 0x38
	private const Int32 WEEK_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_GetIconPos; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ef6920 VA: 0x759550e920
	public Vector2 GetIconPos(GameDayOfWeek day) { }
	// RVA: 0x VA: 0x0
	public Void Render(WeekStruct`1 weekConfig, GetOpenState`1 getAction) { }
	// RVA: 0x2ef6a0c VA: 0x759550ea0c
	public Void .ctor() { }
}
```