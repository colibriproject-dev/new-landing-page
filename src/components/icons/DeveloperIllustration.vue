<template>
  <svg width="400" height="300" viewBox="0 0 400 300" fill="none" xmlns="http://www.w3.org/2000/svg">
    <!-- Background -->
    <rect width="400" height="300" fill="transparent"/>
    
    <!-- Computer Screen -->
    <rect x="50" y="80" width="300" height="180" rx="15" fill="#2C3E50"/>
    <rect x="60" y="90" width="280" height="140" rx="5" fill="#34495E"/>
    <rect x="70" y="100" width="260" height="120" rx="3" fill="#1E2A3A"/>
    
    <!-- Code Lines -->
    <rect x="80" y="110" width="60" height="4" rx="2" fill="#11CDEF"/>
    <rect x="150" y="110" width="40" height="4" rx="2" fill="#5E72E4"/>
    <rect x="200" y="110" width="80" height="4" rx="2" fill="#2DCE89"/>
    
    <rect x="80" y="125" width="40" height="4" rx="2" fill="#5E72E4"/>
    <rect x="130" y="125" width="100" height="4" rx="2" fill="#11CDEF"/>
    
    <rect x="80" y="140" width="80" height="4" rx="2" fill="#2DCE89"/>
    <rect x="170" y="140" width="60" height="4" rx="2" fill="#5E72E4"/>
    
    <rect x="80" y="155" width="50" height="4" rx="2" fill="#11CDEF"/>
    <rect x="140" y="155" width="90" height="4" rx="2" fill="#5E72E4"/>
    
    <rect x="80" y="170" width="70" height="4" rx="2" fill="#2DCE89"/>
    <rect x="160" y="170" width="50" height="4" rx="2" fill="#11CDEF"/>
    
    <rect x="80" y="185" width="60" height="4" rx="2" fill="#5E72E4"/>
    <rect x="150" y="185" width="80" height="4" rx="2" fill="#2DCE89"/>
    
    <rect x="80" y="200" width="90" height="4" rx="2" fill="#11CDEF"/>
    
    <!-- Stand -->
    <rect x="180" y="260" width="40" height="20" fill="#34495E"/>
    <rect x="160" y="270" width="80" height="10" rx="5" fill="#2C3E50"/>
    
    <!-- Floating Elements -->
    <circle cx="350" cy="50" r="20" fill="#11CDEF" opacity="0.3"/>
    <rect x="320" y="40" width="15" height="15" rx="3" fill="#5E72E4" opacity="0.4"/>
    <circle cx="380" cy="80" r="12" fill="#2DCE89" opacity="0.3"/>
    
    <circle cx="30" cy="40" r="15" fill="#5E72E4" opacity="0.3"/>
    <rect x="15" y="70" width="12" height="12" rx="2" fill="#11CDEF" opacity="0.4"/>
    
    <!-- Connection Lines -->
    <path d="M330 60L350 40" stroke="#11CDEF" stroke-width="2" opacity="0.5"/>
    <path d="M370 70L390 50" stroke="#5E72E4" stroke-width="2" opacity="0.5"/>
    <path d="M20 50L40 70" stroke="#2DCE89" stroke-width="2" opacity="0.5"/>
  </svg>
</template>

<script>
export default {
  name: 'DeveloperIllustration'
}
</script> 