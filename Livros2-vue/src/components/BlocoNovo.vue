<script>
export default {
  data() {
    return {
      livros: [
        {
          nome: "It A Coisa",
          imagem: new URL(
            "https://http2.mlstatic.com/D_NQ_NP_700901-MLB20426409030_092015-O.webp",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/coisa-Stephen-King/dp/8560280944/ref=sr_1_2?crid=EFS8L95RBXAJ&keywords=it+a+coisa&qid=1652118373&s=books&sprefix=it+%2Cstripbooks%2C241&sr=1-2&ufe=app_do%3Aamzn1.fos.fcd6d665-32ba-4479-9f21-b774e276a678",
          tipo: "Livro",
          locais: "Cine Vision, HBO Max, Globoplay, Youtube",
        },

        {
          nome: "Cemitério Maltido",
          imagem: new URL(
            "https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQbrXnBvggEs__rCVrZXZPybR8uVidu8REudotCScJ4su7xr1l8",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/dp/8581050395/ref=emc_b_5_i",
          tipo: "Livro",
          locais: "Cine Vision, Netflix, Amazon, Youtube",
        },

        {
          nome: "Invocadores Do Mal",
          imagem: new URL(
            "https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQT4xWln_RuDuVE5b8dFR14DrYEKsxw6SQ_4h7r7GpCT-kAvPaL",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/Invocadores-do-Mal-Cheryl-Wicks-ebook/dp/B01JMAT982/ref=sr_1_2?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1OZFGH57MXFMR&keywords=invoca%C3%A7ao+do+mal+1&qid=1652117299&sprefix=invoca%C3%A7ao+do+mal+1%2Caps%2C222&sr=8-2",
          tipo: "Livro",
          locais: "Cine Vision, HBO Max, Amazon, Youtube",
        },

        {
          nome: "Carrie a Estranha",
          imagem: new URL(
            "https://images-na.ssl-images-amazon.com/images/I/81FXB4eghEL.jpg",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/Carrie-estranha-Stephen-King/dp/8581050360/ref=pd_rhf_se_s_pd_sbs_rvi_sccl_1_7/134-6198485-4278716?pd_rd_w=Jmcr2&pf_rd_p=20983a13-7c61-4a04-a8f4-d0a8f70a3084&pf_rd_r=VPKN4KA2RS8ZD54NXDFJ&pd_rd_r=df92fc48-9b93-4a4c-b1a8-a4d20b568351&pd_rd_wg=DGarK&pd_rd_i=8581050360&psc=1",
          tipo: "Livro",
          locais: "Amazon, Google Play Filmes, Youtube",
        },

        {
          nome: "Divergente",
          imagem: new URL(
            "https://loja.taglivros.com/media/catalog/product/cache/1/image/278x425/9df78eab33525d08d6e5fb8d27136e95/d/i/divergente.png",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/Divergente-Escolha-Transformar-Trilogia-Livro/dp/8579801311/ref=pd_bxgy_img_sccl_2/143-3849621-4314565?pd_rd_w=rgv8g&pf_rd_p=f6d6e5b8-8da7-4a7b-8303-08e67f79afcf&pf_rd_r=7C8Q70VD6KH5D462HC5B&pd_rd_r=34a9f0f7-4229-4b94-be8c-ef0fb08ff0a7&pd_rd_wg=9q78r&pd_rd_i=8579801311&psc=1",
          tipo: "Livro",
          locais: "Cine Vision, HBO Max, Globoplay, Youtube, Netflix, Amazon, entre outros",
        },

        {
          nome: "Insurgente",
          imagem: new URL(
            "http://1.bp.blogspot.com/-af1t_X3GUg4/UzBEMKV_jXI/AAAAAAAAAtE/Eu8c3koea0I/s1600/EUA.jpg",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/Insurgente-Uma-Escolha-Pode-Destruir/dp/8579801559/ref=pd_sbs_sccl_2_1/143-3849621-4314565?pd_rd_w=HP83n&pf_rd_p=1eb83ecb-3d38-4c15-9700-c733345d3c82&pf_rd_r=VRRR3J4E6T7DH3KGTG8F&pd_rd_r=07e5b59e-5bed-421d-bcf2-67f172eac5cb&pd_rd_wg=jp4YW&pd_rd_i=8579801559&psc=1",
          tipo: "Livro",
          locais: "Cine Vision, HBO Max, Globoplay, Youtube, Netflix, Amazon, entre outros",
        },

        {
          nome: "Convergente",
          imagem: new URL(
            "https://loja.taglivros.com/media/catalog/product/cache/1/image/278x425/9df78eab33525d08d6e5fb8d27136e95/c/o/convergente.png",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/Convergente-Escolha-Definir-Trilogia-Divergente/dp/8579801869/ref=pd_sbs_sccl_2_1/143-3849621-4314565?pd_rd_w=Osazm&pf_rd_p=1eb83ecb-3d38-4c15-9700-c733345d3c82&pf_rd_r=QGNRXQ192EZKRSW3CWRH&pd_rd_r=1166f6be-5818-402d-a069-9c0bac55ba3f&pd_rd_wg=kWalx&pd_rd_i=8579801869&psc=1",
          tipo: "Livro",
          locais: "Cine Vision, HBO Max, Globoplay, Youtube, Netflix, Amazon, entre outros",
        },


        {
          nome: "Jogos Vorazes",
          imagem: new URL(
            "https://images-na.ssl-images-amazon.com/images/I/61zBhzjS4LL.jpg",
            import.meta.url
          ).href,
          link: "https://www.amazon.com.br/Jogos-Vorazes-1-Suzanne-Collins/dp/8579800242/ref=sr_1_3?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1VLV6XFK55P0E&keywords=jogos+vozares&qid=1652270502&sprefix=jogos+vozares%2Caps%2C285&sr=8-3",
          tipo: "Livro",
          locais: "Amazon, HBO Max, Globoplay, Youtube",
        },
      ],
    };
  },
};
</script>
<template>
  <article v-for="(livro, i) of livros" :key="i" class="block">
    <h1>{{livro.nome}}</h1>
    <figure>
      <img :src="livro.imagem" width="100" />
    </figure>
    <a :href="livro.link">{{ livro.tipo }}</a>
    <h4>Onde encontrar os filmes</h4>
    <p>{{ livro.locais }}</p>
  </article>

 
</template>
