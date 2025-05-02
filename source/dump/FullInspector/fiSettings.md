# fiSettings

**Namespace:** `FullInspector`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class fiSettings
{
	public static Boolean EnableLogs; // 0x0
	public static Boolean PrettyPrintSerializedJson; // 0x1
	public static CommentType DefaultCommentType; // 0x4
	public static Boolean ForceDisplayInlineObjectEditor; // 0x8
	public static Boolean EnableAnimation; // 0x9
	public static Boolean ForceSaveAllAssetsOnSceneSave; // 0xa
	public static Boolean ForceSaveAllAssetsOnRecompilation; // 0xb
	public static Boolean ForceRestoreAllAssetsOnRecompilation; // 0xc
	public static Boolean AutomaticReferenceInstantation; // 0xd
	public static Boolean InspectorAutomaticReferenceInstantation; // 0xe
	public static Boolean InspectorRequireShowInInspector; // 0xf
	public static Boolean SerializeAutoProperties; // 0x10
	public static Boolean EmitWarnings; // 0x11
	public static Boolean EmitGraphMetadataCulls; // 0x12
	public static Single MinimumFoldoutHeight; // 0x14
	public static Boolean EnableOpenScriptButton; // 0x18
	public static Boolean ForceDisableMultithreadedSerialization; // 0x19
	public static Single LabelWidthPercentage; // 0x1c
	public static Single LabelWidthOffset; // 0x20
	public static Single LabelWidthMax; // 0x24
	public static Single LabelWidthMin; // 0x28
	public static Boolean DisplaySingleCategory; // 0x2c
	public static Int32 DefaultPageMinimumCollectionLength; // 0x30
	public static String RootDirectory; // 0x38
	public static String RootGeneratedDirectory; // 0x40


	// RVA: 0x34cb9dc VA: 0x7595ae39dc
	private static Void .cctor() { }
	// RVA: 0x34cbed8 VA: 0x7595ae3ed8
	private static Void EnsureRootDirectory() { }
	// RVA: 0x34cc50c VA: 0x7595ae450c
	private static String FormatCustomizerForNewPath(String path) { }
	// RVA: 0x34cc150 VA: 0x7595ae4150
	private static String FindDirectoryPathByName(String currentDirectory, String targetDirectory) { }
	// RVA: 0x34cc9f8 VA: 0x7595ae49f8
	public Void .ctor() { }
}
```