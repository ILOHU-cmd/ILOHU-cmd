class BlueTeamAnalyst:
    def __init__(self):
        self.nombre = "Tu Nombre"
        self.rol = "Analista de Datos"
        self.objetivo = "Blue Team Specialist"
        self.ubicacion = "Bucaramanga, Colombia"
        
    def habilidades_actuales(self):
        return {
            "analisis": ["Python", "Pandas", "Data Analysis"],
            "aprendiendo": ["SQL", "Linux Logs", "SIEM"],
            "intereses": ["Threat Detection", "Security Analytics", "SOC"]
        }
    
    def mision(self):
        return "Proteger sistemas mediante análisis de datos y detección de amenazas"
