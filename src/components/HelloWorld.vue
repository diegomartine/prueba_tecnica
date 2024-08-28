<style scoped>
.image_tamaño {
  width: 20px;
  height: 20px;
}
.file-preview {
  margin-top: 10px;
}
.cropper-container {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
}
.cropper-container img {
  width: 100%;
  height: auto;
}
.modal-content button {
  z-index: 1002;
}

.color-principal {
  background-color: #1f1e1e;
  color: white;
  padding: 20px;
  font-family: Arial, sans-serif;
  max-width: 600px;
  margin: auto;
  border: none;
  border-radius: none;
}
.color-secundario {
  background-color: #f0f0f0;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}
.modal {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 1000;
}
.modal-content {
  background: white;
  padding: 20px;
  border-radius: 5px;
  width: 100%;
  max-width: 800px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
.modal-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #ddd;
  padding-bottom: 10px;
}
.modal-title {
  color: #005f00;
  font-size: 18px;
  font-weight: bold;
}
.modal-close {
  font-size: 24px;
  cursor: pointer;
  color: black;
}
.modal-body {
  display: flex;
  flex-direction: column;
}
.modal-actions {
  display: flex;
  flex-direction: column;
}

.cropper-container {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
}
.cropper-container img {
  width: 100%;
  height: auto;
}
.post-button {
  background-color: green;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.error-message {
  color: red;
  font-size: 14px;
}
.icon-list {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}
.select-container {
  margin-bottom: 10px;
}
.box-comments {
  background-color: #4f4d4d;
  margin-top: 20px;
  color: #ffff;
}
.container1 {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}
input[type="text"] {
  border-radius: 50px;
  padding: 15px;
  border: none;
  background-color: #9c9c9c;
}
input[type="text"].expanded {
  width: 100%;
}
.expanded-content {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  margin-top: 10px;
  padding: 7px;
  border-radius: 5px;
  width: 100%;
}
.icon-list {
  display: flex;
  align-items: center;
  gap: 10px;
  border: 2px solid #555;
  border-radius: 8px;
  padding: 10px;
}

.icon-list span {
  font-size: 16px;
  color: #555;
}
.profile-image {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  object-fit: cover;
  border: 2px solid #555;
}
.comments-image {
  width: 40px;
  height: 40px;
  margin-top: 10px;
  margin-left: 10px;
  border-radius: 50%;
  object-fit: cover;
  border: 2px solid #555;
}
.icon-comments {
  width: 25px;
  height: 25px;
}
.icon-wrapper {
  position: relative;
  cursor: pointer;
}
.description {
  display: none;
  position: absolute;
  bottom: -20px;
  left: 50%;
  transform: translateX(-50%);
  background-color: #333;
  color: white;
  padding: 5px;
  border-radius: 3px;
  font-size: 14px;
  white-space: nowrap;
}
.icon-wrapper:hover .description {
  display: block;
}
.select-container {
  flex: 1;
  margin: 0 10px;
}
.cropper-container {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
}
.cropper-container img {
  width: 100%;
  height: auto;
}
.select-container select {
  width: 100%;
  padding: 10px;
  font-size: 16px;
  border-radius: 4px;
  border: 1px solid #ccc;
}
.post-button {
  background-color: green;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  width: 100%;
  max-width: 120px;
}
.post-button:hover {
  background-color: #005f00;
}
.modal {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 1000;
}
.modal-content {
  background: white;
  padding: 20px;
  border-radius: 5px;
  width: 100%;
  max-width: 800px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
.modal-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #ddd;
  padding-bottom: 10px;
}
.modal-title {
  color: #005f00;
  justify-content: flex-start;
  font-size: 18px;
  font-weight: bold;
}
.modal-close {
  font-size: 24px;
  cursor: pointer;
  color: black;
}
.modal-body {
  display: flex;
  align-items: flex-start;
  gap: 20px;
}
.modal-profile-image {
  margin-top: 20px;
  margin-right: 10px;
}
.modal-file-content {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}
input[type="file"] {
  display: none;
}
.box-comments ul {
  display: flex;
  align-items: center;
  list-style: none;
  padding: 0;
  margin: 0;
}
.box-comments ul li {
  margin-right: 10px;
}
.cropper-controls {
  position: absolute;
  top: 10px;
  left: 10px;
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.box-comments ul li img {
  max-width: 20px;
  height: auto;
}
.coment-new {
  margin: 10px;
}
.hover-section:hover {
  background-color: #1f1e1e;
  border-radius: 10px;
}
.editable-div {
  border-radius: 50px;
  padding-top: 8px;
  padding-left: 10px;
  background-color: #9c9c9c;
  min-height: 30px;
  cursor: pointer;
}
.comment-textarea {
  width: 100%;
  height: 80px;
  border-radius: 8px;
  padding: 10px;
  border: 1px solid #ccc;
  resize: none;
  background-color: #9c9c9c;
}
.comment-textarea::placeholder {
  color: #4c4646;
}
.comment-textare {
  width: 100%;
  margin-left: 5px;
  margin-top: 10px;
  margin-bottom: 10px;
  height: 50px;
  border-radius: 8px;
  border: 1px solid #ccc;
  resize: none;
  background-color: #9c9c9c;
}
.comment-textarea::placeholder {
  color: #4c4646;
}
.comment-initial {
  padding: 10px;
  width: 80%;
}
.icon-list2 {
  display: flex;
  justify-content: space-between; 
  width: 95%;
  padding: 10px;
}

.icon-list2 > div {
  flex: 1; 
  text-align: center; 
}
.icon-list2 > div:first-child {
  text-align: left; 
}
.icon-list2 > div:last-child {
  text-align: right; 
}
.liked .icon-comments {
  background-color: #2aee2a;
}

.editable-div {
  border-radius: 50px;
  padding-top: 8px;
  padding-left: 10px;
  background-color: #9c9c9c;
  min-height: 30px;
  cursor: pointer;
  white-space: pre-wrap;
  overflow: hidden;
}
.comment-textarea {
  width: 100%;
  height: 80px;
  border-radius: 8px;
  padding: 10px;
  border: 1px solid #ccc;
  resize: none;
  background-color: #9c9c9c;
  white-space: pre-wrap;
}
.privacy-icon-wrapper {
  position: relative;
  display: inline-block;
}
.tooltip {
  visibility: hidden;
  width: 120px;
  background-color: #333;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;
  position: absolute;
  left: 50%;
  margin-left: -60px;
  opacity: 0;
  transition: opacity 0.3s, visibility 0.3s;
  z-index: 1;
}
.privacy-icon-wrapper:hover .tooltip {
  visibility: visible;
  opacity: 1;
}
.privacy-icon {
  width: 20px;
  height: 20px;
}
.cropper-container {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
}
.cropper-container img {
  width: 100%;
  height: auto;
}
.crop-button {
  background-color: #007bff;
  color: white;
  padding: 8px 16px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
.crop-button:disabled {
  background-color: #6c757d;
  cursor: not-allowed;
}
</style>

<template>
  <div class="color-principal">
    <div><h4>KlipWall</h4></div>

    <div class="color-secundario">
      <div class="container1" @click="handleClickOutside">
        <div class="image-1">
          <img
            src="@/assets/img/inicial.jpg"
            alt="Descriptive image"
            class="profile-image"
          />
        </div>
        <div class="comment-initial">
          <div
            v-if="!inputExpanded"
            @click="expandInput"
            class="editable-div"
            :data-placeholder="placeholderText"
          >
            {{ commentText || placeholderText }}
          </div>
          <textarea
            v-else
            class="comment-textarea"
            v-model="commentText"
            placeholder="Digita tu comentario!"
          ></textarea>
        </div>
      </div>

      <div v-if="inputExpanded" class="expanded-content">
        <div class="icon-list">
          <span>Agrega</span>
          <div class="icon-wrapper" @click="selectFileType('image')">
            <i class="icon">
              <img
                class="image_tamaño"
                src="@/assets/img/photo.png"
                alt="icon"
              />
            </i>
            <div class="description">Foto</div>
          </div>
          <div class="icon-wrapper" @click="selectFileType('video')">
            <i class="icon">
              <img
                class="image_tamaño"
                src="@/assets/img/play_circle.png"
                alt="icon"
              />
            </i>
            <div class="description">Video</div>
          </div>
          <div class="icon-wrapper" @click="selectFileType('audio')">
            <i class="icon">
              <img class="image_tamaño" src="@/assets/img/mic.png" alt="icon" />
            </i>
            <div class="description">Nota de voz</div>
          </div>
          <div class="icon-wrapper" @click="selectFileType('label')">
            <i class="icon">
              <img
                class="image_tamaño"
                src="@/assets/img/label.png"
                alt="icon"
              />
            </i>
            <div class="description">Etiqueta</div>
          </div>
        </div>
        <div class="select-container">
          <select v-model="commentPrivacy">
            <option value="publico">Público</option>
            <option value="privado">Privado</option>
            <option value="solo-para-mi">Solo para mí</option>
          </select>
        </div>
        <div>
          <button class="post-button" @click="postComment">Post</button>
        </div>
      </div>
    </div>

    <!-- Comentarios Generados -->
    <div v-for="(comment, index) in comments" :key="index" class="box-comments">
      <div class="container1">
        <div class="image-1">
          <img
            src="@/assets/img/inicial.jpg"
            alt="User Image"
            class="comments-image"
          />
        </div>
        <div>
          <ul>
            <li>Nombre de artista</li>
            <li><img src="../assets/img/music.png" alt="" /></li>
            <li><img src="../assets/img/check.png" alt="" /></li>
            <li>5 min</li>
            <li class="privacy-icon-wrapper">
              <img
                :src="getPrivacyIcon(comment.privacyIcon)"
                alt="Privacy Icon"
                class="privacy-icon"
              />
              <div class="tooltip">
                {{ getPrivacyDescription(comment.privacyIcon) }}
                <span>{{ comment.privacyIcon }}</span>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="coment-new">
        <div v-if="comment.fileType === 'image'">
          <img
            :src="comment.filePreview"
            alt="Comment Image"
            style="max-width: 100%; height: auto"
          />
        </div>
        <div v-if="comment.fileType === 'video'">
          <video
            :src="comment.filePreview"
            controls
            style="max-width: 100%; height: auto"
          ></video>
        </div>
        <div v-if="comment.fileType === 'audio'">
          <audio
            :src="comment.filePreview"
            controls
            style="max-width: 100%"
          ></audio>
        </div>
        <div v-if="comment.fileType === ''">
          <img
            :src="defaultImage"
            alt="Default Image"
            style="max-width: 100%; height: auto"
          />
        </div>
      </div>
      <div class="coment-new">
        <p>{{ comment.text }}</p>
      </div>
      <div class="icon-list2">
        <div
          class="hover-section"
          :class="{ liked: comment.liked }"
          @click="toggleLike(comment)"
          style="
            display: flex;
            padding: 10px;
            align-items: center;
            justify-content: flex-start;
            width: auto;
          "
        >
          <div class="col">
            <span>
              <img
                src="@/assets/img/like.png"
                alt="Like Icon"
                class="icon-comments"
              />
            </span>
          </div>
          <div class="col">{{ comment.likes }} Likes</div>
        </div>

        <div
          class="hover-section"
          style="
            display: flex;
            padding: 10px;
            align-items: center;
            justify-content: center;
            width: auto;
          "
        >
          <div class="col">
            <span>
              <img
                src="@/assets/img/chat.png"
                alt="Comment Icon"
                class="icon-comments"
              />
            </span>
          </div>
          <div class="col">{{ comment.comments }} Comments</div>
        </div>

        <div
          class="hover-section"
          style="
            display: flex;
            padding: 10px;
            align-items: center;
            justify-content: flex-end;
            width: auto;
          "
        >
          <div class="col">
            <span>
              <img
                src="@/assets/img/share.png"
                alt="Share Icon"
                class="icon-comments"
              />
            </span>
          </div>
          <div class="col">{{ comment.shares }} Shares</div>
        </div>
      </div>
    </div>

    <div v-if="modalVisible" class="modal">
      <div class="modal-backdrop" @click="handleBackdropClick">
        <div class="modal-content" @click.stop>
          <div class="modal-header">
            <h1 class="modal-title">{{ modalTitle }}</h1>
            <span class="modal-close" @click="closeModal">&times;</span>
          </div>

          <div class="modal-body">
            <div v-if="filePreview">
              <div style="display: flex">
                <div class="modal-profile-image">
                  <img
                    src="@/assets/img/inicial.jpg"
                    alt="Descriptive image"
                    class="profile-image"
                  />
                </div>
                <div class="modal-file-content">
                  <div v-if="fileType === 'image'" class="cropper-container">
                    <img ref="image" :src="filePreview" alt="Image Preview" />
                    <div class="cropper-controls">
                      <button
                        v-if="!cropper"
                        class="crop-button"
                        @click="initializeCropper"
                      >
                        Inicializar Cropper
                      </button>
                      <button
                        v-if="cropper"
                        class="crop-button"
                        @click="cropImage"
                      >
                        Recortar Imagen
                      </button>
                    </div>
                  </div>

                  <div v-if="errorMessage" class="error-message">
                    <p>{{ errorMessage }}</p>
                  </div>
                  <div v-if="fileType === 'video'">
                    <video
                      :src="filePreview"
                      controls
                      style="max-width: 100%; height: auto; margin-top: 10px"
                    ></video>
                  </div>
                  <div v-if="fileType === 'audio'">
                    <audio
                      :src="filePreview"
                      controls
                      style="max-width: 100%; top: 10px"
                    ></audio>
                  </div>
                </div>
              </div>
              <div>
                <textarea
                  class="comment-textare"
                  v-model="commentText"
                  placeholder="Digita tu comentario!"
                ></textarea>
              </div>
              <div style="display: flex">
                <div class="icon-list">
                  <span>Agrega</span>
                  <div class="icon-wrapper">
                    <i class="icon">
                      <img
                        class="image_tamaño"
                        src="@/assets/img/photo.png"
                        alt="icon"
                      />
                    </i>
                    <div class="description">Foto</div>
                  </div>
                  <div class="icon-wrapper">
                    <i class="icon">
                      <img
                        class="image_tamaño"
                        src="@/assets/img/play_circle.png"
                        alt="icon"
                      />
                    </i>
                    <div class="description">Video</div>
                  </div>
                  <div class="icon-wrapper">
                    <i class="icon">
                      <img
                        class="image_tamaño"
                        src="@/assets/img/mic.png"
                        alt="icon"
                      />
                    </i>
                    <div class="description">Nota de voz</div>
                  </div>
                  <div class="icon-wrapper">
                    <i class="icon">
                      <img
                        class="image_tamaño"
                        src="@/assets/img/label.png"
                        alt="icon"
                      />
                    </i>
                    <div class="description">Etiqueta</div>
                  </div>
                </div>
                <div class="select-container">
                  <select v-model="commentPrivacy">
                    <option value="publico">Público</option>
                    <option value="privado">Privado</option>
                    <option value="solo-para-mi">Solo para mí</option>
                  </select>
                </div>
                <div>
                  <button class="post-button" @click="postComment">Post</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <input
      type="file"
      ref="fileInput"
      @change="handleFileChange"
      accept="image/*,video/*,audio/*"
      style="display: none"
    />
  </div>
</template>

<script>
import Cropper from "cropperjs";
import "cropperjs/dist/cropper.css";

export default {
  data() {
    return {
      cropper: null,
      isCropping: true,
      inputExpanded: false,
      placeholderText: "Digita tu comentario!",
      fileType: "",
      filePreview: "",
      modalVisible: false,
      modalTitle: "Create post",
      commentPrivacy: "publico",
      comments: [],
      commentText: "",
      defaultImage: require("@/assets/img/inicial.jpg"),
      publico: require("@/assets/img/globe.png"),
      privado: require("@/assets/img/lock.png"),
      errorMessage: "",
      allowedFileTypes: {
        image: ["image/jpeg", "image/png"],
        video: ["video/mp4", "video/webm"],
        audio: ["audio/mpeg", "audio/wav"],
        label: [], 
      },
      hasCropped: false, 
    };
  },
  methods: {
    expandInput(event) {
      this.inputExpanded = true;
      event.stopPropagation();
    },
    handleClickOutside(event) {
      
      if (
        this.inputExpanded &&
        !this.$el.contains(event.target) &&
        event.target.tagName !== "TEXTAREA"
      ) {
        this.collapseInput();
      }
    },
    collapseInput() {
      if (!this.commentText.trim()) {
        this.commentText = "";
      }
      this.inputExpanded = false;
    },
    selectFileType(type) {
      this.fileType = type;
      if (type === "label") {
        this.filePreview = "";
        this.modalTitle = "Etiqueta";
        this.modalVisible = true;
        return;
      }
      this.$refs.fileInput.click();
    },
    handleFileChange(event) {
      const file = event.target.files[0];
      if (file) {
        const validTypes = this.allowedFileTypes[this.fileType] || [];
        if (this.fileType !== "label" && !validTypes.includes(file.type)) {
          this.errorMessage = `El tipo de archivo seleccionado no es válido para ${this.fileType}.`;
          this.filePreview = "";
          this.fileType = "";
          return;
        }
        this.filePreview = URL.createObjectURL(file);
        this.modalVisible = true;
        this.errorMessage = ""; 
      }
    },
    initializeCropper() {
      const image = this.$refs.image;
      if (image && image.complete) {
        if (this.cropper) {
          this.cropper.destroy();
        }
        this.cropper = new Cropper(image, {
          aspectRatio: 1,
          viewMode: 1,
          autoCropArea: 1,
          ready: () => {
            this.isCropping = false; 
          },
        });
      } else {
        image.addEventListener("load", () => {
          if (this.cropper) {
            this.cropper.destroy();
          }
          this.cropper = new Cropper(image, {
            aspectRatio: 1,
            viewMode: 1,
            autoCropArea: 1,
            ready: () => {
              this.isCropping = false;
            },
          });
        });
      }
    },

    cropImage() {
      if (this.hasCropped) {
        this.errorMessage = "Solo se permite un recorte por imagen.";
        return;
      }

      if (this.cropper) {
        const canvas = this.cropper.getCroppedCanvas({
          width: 500,
          height: 400,
        });
        this.filePreview = canvas.toDataURL();
        this.cropper.destroy();
        this.cropper = null; 
        this.isCropping = true; 
        this.hasCropped = true; 
      } else {
        console.error("Cropper no está inicializado.");
      }
    },

    closeModal() {
      this.modalVisible = false;
      this.filePreview = null;
      this.fileType = "";
      this.commentText = "";
      this.hasCropped = false;
      if (this.cropper) {
        this.cropper.destroy();
        this.cropper = null;
      }
      this.isCropping = true;
    },

    postComment() {
      if (this.commentText.trim() === "") {
        alert("Por favor, ingresa un comentario.");
        return;
      }
      this.comments.unshift({
        text: this.commentText,
        fileType: this.fileType,
        filePreview: this.filePreview,
        privacyIcon: this.commentPrivacy,
        likes: 80,
        comments: 10,
        shares: 5,
      });
      this.commentText = "";
      this.fileType = "";
      this.filePreview = null;
      this.commentPrivacy = "publico";
      this.modalVisible = false;
      this.inputExpanded = false;
    },

    handleBackdropClick() {},

    getPrivacyIcon(privacy) {
      switch (privacy) {
        case "publico":
          return this.publico;
        case "privado":
          return this.privado;
        case "solo-para-mi":
          return this.privado;
        default:
          return "";
      }
    },
    toggleLike(comment) {
      comment.liked = !comment.liked;
      comment.likes += comment.liked ? 1 : -1;
    },
    getPrivacyDescription(icon) {
      switch (icon) {
        case this.publico:
          return "Público";
        case this.privado:
          return "Privado";
        case "":
          return "Solo para mí";
        default:
          return "";
      }
    },
  },
  mounted() {
    document.addEventListener("click", this.handleClickOutside);
  },
};
</script>
