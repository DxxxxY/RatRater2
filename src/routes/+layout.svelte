<script>
  import "../app.postcss";
  import { StyleFromScheme } from "m3-svelte";
</script>

<StyleFromScheme
  lightScheme={[
    ["primary", 4278213817],
    ["onPrimary", 4294967295],
    ["primaryContainer", 4292338687],
    ["onPrimaryContainer", 4278197054],
    ["secondary", 4283850353],
    ["onSecondary", 4294967295],
    ["secondaryContainer", 4292535033],
    ["onSecondaryContainer", 4279442475],
    ["tertiary", 4285551989],
    ["onTertiary", 4294967295],
    ["tertiaryContainer", 4294629629],
    ["onTertiaryContainer", 4280816430],
    ["error", 4290386458],
    ["onError", 4294967295],
    ["errorContainer", 4294957782],
    ["onErrorContainer", 4282449922],
    ["background", 4294835199],
    ["onBackground", 4279900958],
    ["surface", 4294835199],
    ["onSurface", 4279900958],
    ["surfaceVariant", 4292928236],
    ["onSurfaceVariant", 4282664782],
    ["outline", 4285822847],
    ["outlineVariant", 4291086032],
    ["shadow", 4278190080],
    ["scrim", 4278190080],
    ["inverseSurface", 4281282611],
    ["inverseOnSurface", 4294045940],
    ["inversePrimary", 4289382399],
  ]}
  darkScheme={[
    ["primary", 4289382399],
    ["onPrimary", 4278202213],
    ["primaryContainer", 4278207886],
    ["onPrimaryContainer", 4292338687],
    ["secondary", 4290692828],
    ["onSecondary", 4280824129],
    ["secondaryContainer", 4282271577],
    ["onSecondaryContainer", 4292535033],
    ["tertiary", 4292721888],
    ["onTertiary", 4282329156],
    ["tertiaryContainer", 4283907676],
    ["onTertiaryContainer", 4294629629],
    ["error", 4294948011],
    ["onError", 4285071365],
    ["errorContainer", 4287823882],
    ["onErrorContainer", 4294957782],
    ["background", 4279900958],
    ["onBackground", 4293124838],
    ["surface", 4279900958],
    ["onSurface", 4293124838],
    ["surfaceVariant", 4282664782],
    ["onSurfaceVariant", 4291086032],
    ["outline", 4287533209],
    ["outlineVariant", 4282664782],
    ["shadow", 4278190080],
    ["scrim", 4278190080],
    ["inverseSurface", 4293124838],
    ["inverseOnSurface", 4281282611],
    ["inversePrimary", 4278213817],
  ]}
/>
<slot />
