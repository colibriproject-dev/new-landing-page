<template>
  <svg width="300" height="250" viewBox="0 0 300 250" fill="none" xmlns="http://www.w3.org/2000/svg">
    <!-- Background -->
    <circle cx="50" cy="50" r="25" fill="#F8F9FA" opacity="0.6"/>
    <circle cx="250" cy="40" r="20" fill="#E9ECEF" opacity="0.5"/>
    <rect x="220" y="180" width="30" height="30" rx="6" fill="#F8F9FA" opacity="0.7"/>
    
    <!-- Phone/Device -->
    <rect x="100" y="60" width="100" height="160" rx="20" fill="#3B4A6B"/>
    <rect x="110" y="80" width="80" height="120" rx="8" fill="#2C3E50"/>
    
    <!-- Screen Content -->
    <rect x="120" y="90" width="60" height="4" rx="2" fill="#11CDEF"/>
    <rect x="120" y="100" width="40" height="4" rx="2" fill="#5E72E4"/>
    <rect x="120" y="110" width="50" height="4" rx="2" fill="#2DCE89"/>
    
    <!-- Message Bubbles -->
    <rect x="125" y="125" width="35" height="15" rx="7" fill="#5E72E4"/>
    <rect x="135" y="145" width="40" height="15" rx="7" fill="#11CDEF"/>
    <rect x="125" y="165" width="30" height="15" rx="7" fill="#2DCE89"/>
    
    <!-- Input Area -->
    <rect x="115" y="185" width="70" height="8" rx="4" fill="#34495E"/>
    
    <!-- Floating Communication Icons -->
    <circle cx="60" cy="100" r="15" fill="#11CDEF" opacity="0.4">
      <animate attributeName="cy" values="100;95;100" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="240" cy="120" r="12" fill="#5E72E4" opacity="0.4">
      <animate attributeName="cy" values="120;115;120" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="70" cy="180" r="10" fill="#2DCE89" opacity="0.4">
      <animate attributeName="cy" values="180;175;180" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    
    <!-- Connection Lines -->
    <path d="M75 110L95 120" stroke="#11CDEF" stroke-width="2" opacity="0.3">
      <animate attributeName="opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/>
    </path>
    <path d="M225 130L205 140" stroke="#5E72E4" stroke-width="2" opacity="0.3">
      <animate attributeName="opacity" values="0.3;0.6;0.3" dur="2.5s" repeatCount="indefinite"/>
    </path>
    
    <!-- Email Symbol -->
    <rect x="40" y="25" width="20" height="15" rx="3" fill="#F5365C" opacity="0.6"/>
    <path d="M40 27L50 33L60 27" stroke="white" stroke-width="1" stroke-linecap="round"/>
    
    <!-- Chat Symbol -->
    <circle cx="250" cy="200" r="15" fill="#2DCE89" opacity="0.6"/>
    <rect x="245" y="195" width="10" height="2" rx="1" fill="white"/>
    <rect x="245" y="199" width="8" height="2" rx="1" fill="white"/>
    <rect x="245" y="203" width="6" height="2" rx="1" fill="white"/>
  </svg>
</template>

<script>
export default {
  name: 'ContactIllustration'
}
</script> 