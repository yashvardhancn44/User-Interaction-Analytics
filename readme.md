# 📊 Real-time User Interaction Analytics.

- 🚀 This project is designed and developed to analyze user interaction 🖱️ in a products page. The events such as buying a product and viewing a product is captured and sent to big data ecoystem (Kafka), from where it can be consumed and analyzed🧮 (eg: Dashboard) for business insights🔍.
- It’s powered by **React**, **Express.js**, **KafkaJS**, **Recharts**, **MongoDB** and **Websockets**. Let's dive into the details! 😎
- ▶️ [**_Demo-video_**](https://www.youtube.com/watch?v=D4jdTxlcTlc)
- [LinkedIn Profile](https://www.linkedin.com/in/yashvardhancn/)
- [Portfolio Website](https://yashvardhan-portfolio.vercel.app/)
- [Email](mailto:yashvardhancn44@gmail.com)

---

## 🛠️ **Tech Stack**

- **Frontend:** React, Recharts
- **Backend:** Express.js, Node.js, KafkaJS, Websockets, Confluent-cloud.
- **Database:** MongoDB with Mongoose.
- **Tools used:** VSCode, Thunder Client extention.

---

## 💡 **Project Features**

- **Capturing Product buying and Product Viewing Events** 🖱️
  User interaction with the website is captured for business insights, and produced to Kafka topics.
- **Storing those events in database for further batch analysis and persistance of data** 🔍  
  The events which are produced to kafka topics are consumed by a consumer which updates the events in Database(MongoDB) for further processing.
- **A Dashboard created to visualize the events for business Insights** 📊  
  The consumer also updates a dahboard created using Recharts, to visualize the event data for better Real-time business insights.

---

## 🚀 **Project in Action:**

Check out ▶️ [**_Demo-video_**](https://www.youtube.com/watch?v=D4jdTxlcTlc).

<p align="left">
  <img src="https://res.cloudinary.com/dxvafakmn/image/upload/v1728124603/kafka-project/j8v9kgn858jsrsrtg1j8.png" alt="add-notes-image" width="400" />
  <img src="https://res.cloudinary.com/dxvafakmn/image/upload/v1728124603/kafka-project/ryzxrap9wwyxe5xm1vcy.png" alt="edit-notes-image" width="400" />
</p>

---

## 🔍 **Project Architecture:**

<p align="left">
  <img src="https://res.cloudinary.com/dxvafakmn/image/upload/v1728124603/kafka-project/fcfsxztkedgoeb8qbszi.png" alt="notes-sd-image" width="500" />
</p>

---

## 🚀 **Getting Started**

### 1. **Clone the Repositories**

### 2. **Install Dependencies**

- Install Dependencies in each directory. `npm install`

### 3. **Add Environment Variables**

### 4. **Run the project**

- For Frontend `npm run dev`
- For backend `node server.js`
