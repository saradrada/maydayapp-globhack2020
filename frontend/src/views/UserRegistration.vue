<template>
    <div>
        <form @submit.prevent="handleSubmit"
        @submit="submitRegisterForm">

            <base-input label="Nombre"
              type="text"
              placeholder="Nombre"
              name="first_name"
              required
              v-model="user.first_name"></base-input>

            <base-input label="Apellido"
              type="text"
              placeholder="Apellido"
              name="last_name"
              required
              v-model="user.last_name"></base-input>

            <base-input label="Documento de identidad"
              type="number"
              placeholder="Documento"
              name="document_number"
              required
              v-model="user.document_number"></base-input>
            
            <base-input label="Fecha de Nacimiento"
              type="date"
              name="birthdate"
              required
              v-model="user.birthdate"></base-input>
            
            <div v-if="userType === 'health'">
                <base-input label="Numero Tarjeta profesional"
                    type="number"
                    placeholder="Numero Tarjeta profesional"
                    name="professionalCardNumber"
                    required
                    v-model="user.professional_card_number"></base-input>
                
                <base-input label="Area de la Salud"
                    type="text"
                    placeholder="Area de la Salud"
                    name="healtArea"
                    required
                    v-model="user.health_area"></base-input>
            </div>
            
            <base-input label="Correo Electronico"
              type="text"
              placeholder="Correo"
              name="email"
              required
              v-model="user.email"></base-input>

            <base-input label="Contraseña"
              type="password"
              name="password"
              required
              v-model="user.password"></base-input>

            <base-input label="Confirmar Contraseña"
              type="password"
              name="confirm_password"
              required></base-input>

            <base-input label="Número telefónico"
              type="number"
              name="phone_number"
              v-model="user.phone_number"></base-input>

            <div class="col-md-12">
              <base-input label="Breve Description">
                <textarea
                  placeholder="Breve descripción sobre tu persona"
                  name="description"
                  v-model="user.description"
                ></textarea>
              </base-input>
            </div>

            <input type="submit" value="Registrarme!">
        </form>
    </div>
</template>

<script>
export default {
    props:['userType'],
    data() {
    return {
      user: {
        first_name: "",
        last_name: "",
        document_number: "",
        professional_card_number: "",
        email: "",
        password: "",
        phone_number: "",
        description: "",
        health_area:"",
        birthdate:"",
      },
    };
  },
    methods: {
        submitRegisterForm() {
            
        },
    }
}
</script>