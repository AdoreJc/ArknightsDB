# MultiplayerLogUploader

**Namespace:** `Torappu.Multiplayer`


## Fields

- `HttpUpload m_uploader`

- `Boolean m_enableCompress`


## Methods

- `Void InitIfNot()`

- `Void _TryUploadNext()`

- `Void _SendToServer(String, String, String)`

- `Void _PostToPrivateServer(String, String)`

- `String _CompressContent(Stream)`

- `Void _Close()`

- `Void <_SendToServer>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MultiplayerLogUploader : SingletonMonoBehaviour`1
{
	public static Boolean s_closedByServer; // 0x0
	private const Int32 MAX_LOG_LENGTH; // 0x0
	private HttpUpload m_uploader; // 0x18
	private Boolean m_enableCompress; // 0x20
	private Queue`1 m_logs; // 0x28
	private static DelegateBridge __Hotfix0_TryStartUpload; // 0x8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0__TryUploadNext; // 0x20
	private static DelegateBridge __Hotfix0__SendToServer; // 0x28
	private static DelegateBridge __Hotfix0__PostToPrivateServer; // 0x30
	private static DelegateBridge __Hotfix0__CompressContent; // 0x38
	private static DelegateBridge __Hotfix0__Close; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x3592ddc VA: 0x7595baaddc
	public static Void TryStartUpload() { }
	// RVA: 0x3592e70 VA: 0x7595baae70
	public Void InitIfNot() { }
	// RVA: 0x3592ed4 VA: 0x7595baaed4
	protected override Void OnInit() { }
	// RVA: 0x3592ff8 VA: 0x7595baaff8
	private Void _TryUploadNext() { }
	// RVA: 0x35933e0 VA: 0x7595bab3e0
	private Void _SendToServer(String actID, String sceneID, String localPath) { }
	// RVA: 0x35931c8 VA: 0x7595bab1c8
	private Void _PostToPrivateServer(String remotePath, String localPath) { }
	// RVA: 0x359371c VA: 0x7595bab71c
	private String _CompressContent(Stream logFile) { }
	// RVA: 0x3593124 VA: 0x7595bab124
	private Void _Close() { }
	// RVA: 0x35938d0 VA: 0x7595bab8d0
	protected override Void OnDestroy() { }
	// RVA: 0x3593984 VA: 0x7595bab984
	public Void .ctor() { }
	// RVA: 0x3593a14 VA: 0x7595baba14
	private Void <_SendToServer>b__9_0() { }
}
```